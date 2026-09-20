<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9lre6i7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smart-screen-sharp" /></template>
<style>
.v9lre6i7s {
  fill: currentColor;
  d: path("M2 18V6h20v12zm3.5-1h13V7h-13zm7.75-4.365q-.275 0-.455-.18t-.18-.455t.18-.455t.455-.18t.455.18t.18.455t-.18.455t-.455.18m-5 0q-.275 0-.455-.18T7.615 12t.18-.455t.455-.18t.455.18t.18.455t-.18.455t-.455.18m7.5 0q-.275 0-.455-.18t-.18-.455t.18-.455t.455-.18t.455.18t.18.455t-.18.455t-.455.18m-5 0q-.275 0-.455-.18t-.18-.455t.18-.455t.455-.18t.455.18t.18.455t-.18.455t-.455.18");
}

</style>
