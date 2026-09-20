<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3ydiqi0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-3-outline-sharp" /></template>
<style>
.b3ydiqi0s {
  fill: currentColor;
  d: path("M5.98 19H18V4H5.98zm2.712 2v-1H4.981V3H19v17h-3.73v1zM12 11.5");
}

</style>
