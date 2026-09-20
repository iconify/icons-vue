<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cvhf4lbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-link-20-filled" /></template>
<style>
.cvhf4lbfi {
  fill: currentColor;
  d: path("M5.496 3a2.5 2.5 0 0 0-2.5 2.5v9a2.5 2.5 0 0 0 2.5 2.5h3.54a3.5 3.5 0 0 1 3.465-4H16.5q.252 0 .496.035V7h-7.5a1.5 1.5 0 0 1-1.5-1.5V3zm3.5 0v2.5a.5.5 0 0 0 .5.5h7.5v-.5a2.5 2.5 0 0 0-2.5-2.5zM12.5 14a2.5 2.5 0 0 0 0 5h.5a.5.5 0 0 0 0-1h-.5a1.5 1.5 0 0 1 0-3h.5a.5.5 0 0 0 0-1zm3.5 0a.5.5 0 0 0 0 1h.5a1.5 1.5 0 0 1 0 3H16a.5.5 0 0 0 0 1h.5a2.5 2.5 0 0 0 0-5zm-4 2.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5");
}

</style>
