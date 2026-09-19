<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="eaixg9eok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:water-closet" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.eaixg9eok {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.6 45L11 19h4l2.9 17.9L21.4 19H26l3.4 18.2L32.3 19h3.9l-4.7 26h-4.1l-3.8-19.4L19.8 45zM46 41.3c-1.9 0-3.5-1.7-3.5-3.7V26.4c0-2 1.6-3.7 3.5-3.7s3.5 1.7 3.5 3.7H53c0-4.1-3.1-7.4-7-7.4s-7 3.3-7 7.4v11.1c0 4.1 3.1 7.4 7 7.4s7-3.3 7-7.4h-3.5c0 2.1-1.6 3.8-3.5 3.8");
}

</style>
