<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq9n4p9zf"/><path class="q8-yo_fog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-settings-input-hdmi" /></template>
<style>
.jq9n4p9zf {
  fill: currentColor;
  d: path("M8 9H7v3.53l2.79 5.58l.21.42V20h4v-1.47l.21-.42L17 12.53V9h-1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q8-yo_fog {
  fill: currentColor;
  d: path("M18 7V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2v3H5v6l3 6v3h8v-3l3-6V7zM8 4h8v3h-2.01V5h-1v2H11V5h-1v2H8zm9 8.53l-3 6V20h-4v-1.47l-3-6V9h10z");
}

</style>
