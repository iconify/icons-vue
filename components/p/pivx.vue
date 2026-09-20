<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xu114rbwc"><path class="qoaen17-d"/><path class="t9i6qbbca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pivx" /></template>
<style>
.qoaen17-d {
  d: path("M12.9 4.8H5.7V3h7.2a5.4 5.4 0 0 1 0 10.8H7.5V21H5.7v-9h7.2a3.6 3.6 0 0 0 0-7.2");
}

.t9i6qbbca {
  d: path("M11.7 9h-6V7.2h6z");
}

.xu114rbwc {
  fill: var(--svg-color--5e4778, #5e4778);
}

</style>
