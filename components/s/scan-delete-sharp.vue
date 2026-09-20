<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guc2h195i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scan-delete-sharp" /></template>
<style>
.guc2h195i {
  fill: currentColor;
  d: path("M13 9h5l-5-5zm2.9 12.5l-1.4-1.4l2.1-2.1l-2.1-2.1l1.4-1.4l2.1 2.1l2.1-2.1l1.4 1.4l-2.075 2.1l2.075 2.1l-1.4 1.4l-2.1-2.075zM4 22V2h10l6 6v4.35q-.475-.175-.975-.262T18 12q-2.5 0-4.25 1.738T12 17.975q0 1.125.4 2.163T13.55 22z");
}

</style>
