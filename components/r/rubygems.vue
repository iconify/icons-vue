<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":293};
const content = `<g class="i160q39rf"><path class="jhull5b7o"/><path class="dgr__5rtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:rubygems" /></template>
<style>
.dgr__5rtu {
  d: path("M127.823.976L.135 74.173v146.395l127.688 73.197l127.689-73.197V74.173zm103.29 205.603l-103.29 59.534l-103.29-59.534V87.837l103.29-59.534l103.29 59.534z");
}

.i160q39rf {
  fill: var(--svg-color--d34231, #d34231);
}

.jhull5b7o {
  d: path("m76.748 97.434l-.163-.163l-36.11 36.11l87.674 87.512l36.11-35.948l51.564-51.563l-36.11-36.11v-.164H76.584z");
}

</style>
