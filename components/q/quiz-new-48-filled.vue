<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pw37x1ilb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-new-48-filled" /></template>
<style>
.pw37x1ilb {
  fill: currentColor;
  d: path("M35 24c6.075 0 11 4.925 11 11s-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11m0 3a1 1 0 0 0-1 1v6h-6a1 1 0 1 0 0 2h6v6a1 1 0 1 0 2 0v-6h6a1 1 0 1 0 0-2h-6v-6a1 1 0 0 0-1-1m.75-21A6.25 6.25 0 0 1 42 12.25v11.793A12.94 12.94 0 0 0 35 22c-4.6 0-8.643 2.39-10.954 5.995H12.25a1.25 1.25 0 0 0 0 2.5h10.552A13 13 0 0 0 22.038 34H12.25a1.25 1.25 0 1 0 0 2.5h9.836c.23 2.008.919 3.877 1.958 5.5H12.25A6.25 6.25 0 0 1 6 35.75v-23.5A6.25 6.25 0 0 1 12.25 6zm-16.252 4.998a1.25 1.25 0 0 0-1.155.774l-4.748 11.505a1.25 1.25 0 0 0 2.31.954l.707-1.713h5.775l.708 1.713a1.25 1.25 0 0 0 2.31-.954l-4.752-11.506a1.25 1.25 0 0 0-1.155-.773m12.25 0c-.69 0-1.25.56-1.25 1.25V15H27.75a1.25 1.25 0 1 0 0 2.5h2.748v2.748a1.25 1.25 0 0 0 2.5 0V17.5h2.752a1.25 1.25 0 0 0 0-2.5h-2.752v-2.752c0-.69-.56-1.25-1.25-1.25m-10.393 9.02h-3.711l1.854-4.494z");
}

</style>
