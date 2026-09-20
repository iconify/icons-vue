<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="ig8hrw-ms"/><path class="tdyyz6ben"/><path class="dezhh5b7g"/><path class="pbbwb6wkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:ping-pong" /></template>
<style>
.dezhh5b7g {
  fill: var(--svg-color--fdcb80, #fdcb80);
  d: path("M68.43 91.38L32.31 63.52s7.35 14.05 1.78 23.65c-4.36 7.5-10.37 13.76-15.64 18.98a2.942 2.942 0 0 0 .28 4.43l7.17 5.53c1.41 1.09 3.46.69 4.36-.86c3.71-6.42 8.85-13.63 15-19.75c7.85-7.83 23.17-4.12 23.17-4.12");
}

.ig8hrw-ms {
  cx: 91.38px;
  cy: 108.35px;
  r: 11.83px;
  fill: var(--svg-color--fbc21a, #fbc21a);
}

.pbbwb6wkz {
  fill: var(--svg-color--f9ae4b, #f9ae4b);
  d: path("m33.32 90.3l9.51-11.97a3.44 3.44 0 0 1 4.82-.62l3.94 3.05a3.44 3.44 0 0 1 .65 4.79l-8.73 10.91c-.11.16-.32.2-.44.11c-.14-.09-.17-.33-.02-.49c1.97-3.11 3.93-6.3 5.9-9.41c.72-1.13.46-2.62-.6-3.44l-2.27-1.7a2.585 2.585 0 0 0-3.5.31l-8.83 8.76c-.13.18-.36.19-.45.1c-.08-.09-.08-.26.02-.4");
}

.tdyyz6ben {
  fill: var(--svg-color--e5502e, #e5502e);
  d: path("M104.16 71.54c13.89-20.66 16.98-42.34-4.06-58.56C79.07-3.25 58.89 5.24 42.43 23.92c-18.88 21.43-10.12 39.6-10.12 39.6l36.12 27.86s19.8 3.86 35.73-19.84");
}

</style>
