<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ug9-2zbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:medium-skin-tone" /></template>
<style>
.ug9-2zbjl {
  fill: var(--svg-color--bf8f68, #bf8f68);
  d: path("M10 10h108v108H10z");
}

</style>
