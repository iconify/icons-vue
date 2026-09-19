<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><g class="n1mjunbsu"><path class="cicicobsr"/><path class="waco96m9s"/><path class="hjtw-db4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:repeat-single-button" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.cicicobsr {
  d: path("M47.3 23.7L36 17v3.8H24.4c-2.8 0-5.4 1.1-7.4 3.1s-3 4.8-3 7.6c0 1.2.2 2.3.5 3.4c.2-.3.5-.7.8-1c.7-.8 1.6-1.4 2.6-1.8c.6-.2 1.2-.4 1.8-.5v-.1c0-2.7 2.1-4.9 4.7-4.9H36v3.8z");
}

.hjtw-db4l {
  d: path("M21.8 42.7h-1.1v-4.3c-.4.4-.9.7-1.4.9v-1c.3-.1.6-.3.9-.5c.3-.3.6-.6.7-.9h.9z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.waco96m9s {
  d: path("m49.5 28.1l-5.2 3.1v.4c0 2.7-2.1 4.9-4.7 4.9H27.2c-1.2-2.3-3.5-3.8-6.2-3.8c-3.9 0-7 3.2-7 7.2s3.2 7.2 7 7.2c3.1 0 5.7-2 6.6-4.8h11.9c2.8 0 5.4-1.1 7.4-3.1s3.1-4.7 3.1-7.6c0-1.3-.2-2.4-.5-3.5M21 44.6c-2.6 0-4.7-2.2-4.7-4.8c0-2.7 2.1-4.8 4.7-4.8s4.7 2.2 4.7 4.8c.1 2.6-2.1 4.8-4.7 4.8");
}

</style>
