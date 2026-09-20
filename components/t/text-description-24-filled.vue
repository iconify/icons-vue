<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_tl-rbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-description-24-filled" /></template>
<style>
.l_tl-rbkf {
  fill: currentColor;
  d: path("M3 17h12a1 1 0 0 1 .117 1.993L15 19H3a1 1 0 0 1-.117-1.993zh12zm0-4h18a1 1 0 0 1 .117 1.993L21 15H3a1 1 0 0 1-.117-1.993zh18zm0-4h18a1 1 0 0 1 .117 1.993L21 11H3a1 1 0 0 1-.117-1.993zh18zm0-4h18a1 1 0 0 1 .117 1.993L21 7H3a1 1 0 0 1-.117-1.993zh18z");
}

</style>
