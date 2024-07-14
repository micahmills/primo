<script>
  import { PrimoPage } from '@centralasiade/builder'

  export let data
</script>

<PrimoPage
  page={{
    ...data.page,
    sections: data.sections,
  }}
/>
