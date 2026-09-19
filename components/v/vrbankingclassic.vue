<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lk6ldbcvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vrbankingclassic" /></template>
<style>
.lk6ldbcvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.484 30.337H43.5v-19.5h-39v19.5h14.016l-1.828-8.53h-4.875l-1.22-4.876h10.36L24 30.337l2.072-9.75c.703-3.31 2.232-3.656 5.24-3.656h6.094l-1.584 7.313a2.06 2.06 0 0 1-1.95 1.584c-.689-.064-1.721-.656-1.585-1.34l.366-1.829a.72.72 0 0 0-.731-.853a.94.94 0 0 0-.853.731ZM4.5 30.338v6.824h15.478l-1.462-6.824m10.968-.001l-1.462 6.825H43.5v-6.824");
}

</style>
