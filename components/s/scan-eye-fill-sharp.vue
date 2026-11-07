<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzuuvk04i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-eye-fill-sharp" /></template>
<style>
.pzuuvk04i {
  fill: currentColor;
  d: path("M2 7V3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0m15-5h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2M4.168 11.445c4.4-6.597 11.264-6.597 15.664 0a1 1 0 0 1 0 1.11c-4.4 6.597-11.264 6.597-15.664 0a1 1 0 0 1 0-1.11M17.779 12c-3.442-4.664-8.116-4.664-11.558 0c3.442 4.664 8.116 4.664 11.558 0M12 11h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2M3 22a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2Zm19-5v4a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0");
}

</style>
