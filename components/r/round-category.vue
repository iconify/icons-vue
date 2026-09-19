<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehyvx_nni"/><circle class="u1l7rqbek"/><path class="kuunmhbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-category" /></template>
<style>
.ehyvx_nni {
  fill: currentColor;
  d: path("M11.15 3.4L7.43 9.48c-.41.66.07 1.52.85 1.52h7.43c.78 0 1.26-.86.85-1.52L12.85 3.4a.993.993 0 0 0-1.7 0");
}

.kuunmhbmt {
  fill: currentColor;
  d: path("M4 21.5h6c.55 0 1-.45 1-1v-6c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1");
}

.u1l7rqbek {
  cx: 17.5px;
  cy: 17.5px;
  r: 4.5px;
  fill: currentColor;
}

</style>
