<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha-2ihbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-missed-video-call" /></template>
<style>
.ha-2ihbgs {
  fill: currentColor;
  d: path("M17 10.5V6H3v12h14v-4.5l4 4v-11zM10 15l-3.89-3.89v2.55H5V9.22h4.44v1.11H6.89l3.11 3.1l4.22-4.22l.78.79z");
}

</style>
