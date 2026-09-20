<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5wwkguwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:web-stories-sharp" /></template>
<style>
.k5wwkguwp {
  fill: currentColor;
  d: path("M17.116 19.596V4.385H18.5v15.211zm-13 1.635V2.769h12v18.462zM19.5 17.98V6h.885v11.98z");
}

</style>
