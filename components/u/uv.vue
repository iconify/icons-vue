<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b6it62y-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:uv" /></template>
<style>
.b6it62y-r {
  fill: var(--svg-color--de5fe9, #de5fe9);
  d: path("m0 1.075l.537 127.517l.43 102.012c.06 14.085 11.521 25.455 25.6 25.396l101.97-.43l63.732-.269l6.48-.027c14.037-.06 25.385-11.7 25.385-25.743h11.676v25.498l20.19.003L254.925 0L137.66.495l.494 101.637v63.64h-20.889l.495-63.554L117.265.58z");
}

</style>
