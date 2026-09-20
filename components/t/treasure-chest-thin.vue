<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cefii7gst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:treasure-chest-thin" /></template>
<style>
.cefii7gst {
  fill: currentColor;
  d: path("M184 44H72a52.06 52.06 0 0 0-52 52v96a12 12 0 0 0 12 12h192a12 12 0 0 0 12-12V96a52.06 52.06 0 0 0-52-52m44 52v12h-40V52.19A44.06 44.06 0 0 1 228 96m-88 44h-24v-40h24Zm-28 8h32a4 4 0 0 0 4-4v-28h32v80H76v-80h32v28a4 4 0 0 0 4 4m36-40V96a4 4 0 0 0-4-4h-32a4 4 0 0 0-4 4v12H76V52h104v56ZM68 52.19V108H28V96a44.06 44.06 0 0 1 40-43.81M28 192v-76h40v80H32a4 4 0 0 1-4-4m196 4h-36v-80h40v76a4 4 0 0 1-4 4");
}

</style>
