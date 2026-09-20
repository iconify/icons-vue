<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wqbq3pbgh"/><path class="cy-_o3ded"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:parsehub" /></template>
<style>
.cy-_o3ded {
  fill: var(--svg-color--20222d, #20222d);
  d: path("M256 20.48C256 9.216 246.12 0 234.856 0h-104.25C59.915 0 0 56.027 0 126.72V256h31.086V126.72c0-53.64 44.761-97.28 98.4-97.28s97.838 43.639 97.838 97.28S183.027 224 129.388 224c-25.735 0-52.588-10.06-67.217-26.432V256h68.435C201.298 256 256 197.413 256 126.72z");
}

.wqbq3pbgh {
  fill: var(--svg-color--21bbd1, #21bbd1);
  d: path("M64.046 126.72c0-36.7 29.858-66.56 66.56-66.56c36.7 0 66.56 29.86 66.56 66.56s-29.86 66.56-66.56 66.56c-36.702 0-66.56-29.859-66.56-66.56");
}

</style>
