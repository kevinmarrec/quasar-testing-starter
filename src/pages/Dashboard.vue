<template lang="pug">
  q-page.flex.flex-center
    .column.flex-center
      p {{ $t('pages.dashboard.title') }}
</template>

<style>
</style>

<script>
export default {
  name: 'PageDashboard',
  meta () {
    return {
      title: 'Dashboard'
    }
  }
}
</script>
