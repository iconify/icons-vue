<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="op1yydbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:molecule-28-filled" /></template>
<style>
.op1yydbdp {
  fill: currentColor;
  d: path("M19 14a6 6 0 1 0-5.364-3.31l-3.359 2.363a4.5 4.5 0 1 0-.3 5.302l5.203 3.035a3.5 3.5 0 1 0 .77-1.287l-5.226-3.049a4.5 4.5 0 0 0 .156-2.591l3.592-2.526A6 6 0 0 0 19 14");
}

</style>
