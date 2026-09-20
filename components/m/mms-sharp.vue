<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0k0y_bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mms-sharp" /></template>
<style>
.j0k0y_bfo {
  fill: currentColor;
  d: path("M7.5 13.308h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM3 20.077V3h18v14H6.077z");
}

</style>
