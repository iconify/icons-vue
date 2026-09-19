<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="gl5rwoxvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:right-arrow-curving-up" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.gl5rwoxvu {
  fill: var(--svg-color--fff, #fff);
  d: path("M40.4 19.5v21.2c0 6.8-5.6 12.3-12.5 12.3c-3.3 0-6.5-1.3-8.9-3.6l5.1-5c1 1 2.4 1.5 3.8 1.5c3 0 5.4-2.4 5.4-5.3V19.5h-4.6l8.2-8.5l8.2 8.5z");
}

</style>
