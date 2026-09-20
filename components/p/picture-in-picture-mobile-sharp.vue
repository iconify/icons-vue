<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdp6gwbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-mobile-sharp" /></template>
<style>
.vdp6gwbtk {
  fill: currentColor;
  d: path("M20 22H4V2h16zm-3-9V5h-6v8z");
}

</style>
