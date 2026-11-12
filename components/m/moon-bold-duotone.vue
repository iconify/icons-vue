<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oyt4yhbtg"/><path class="p4ej_wfwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:moon-bold-duotone" /></template>
<style>
.oyt4yhbtg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 12C22 17.5228 17.5228 22 12 22C10.8358 22 9.71801 21.801 8.67887 21.4353C8.24138 20.3767 8 19.2165 8 18C8 15.7787 8.80467 13.7455 10.1384 12.1757C11.31 13.8814 13.2744 15 15.5 15C17.8615 15 19.9289 13.7406 21.0672 11.8568C21.3065 11.4608 22 11.5373 22 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.p4ej_wfwi {
  fill: currentColor;
  d: path("M2 12C2 16.3586 4.78852 20.0659 8.67887 21.4353C8.24138 20.3768 8 19.2166 8 18C8 15.7788 8.80467 13.7455 10.1384 12.1758C9.42027 11.1303 9 9.86422 9 8.5C9 6.13845 10.2594 4.07105 12.1432 2.93276C12.5392 2.69347 12.4627 2 12 2C6.47715 2 2 6.47715 2 12Z");
}

</style>
