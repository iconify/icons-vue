<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzzk90jnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-eye-fill" /></template>
<style>
.xzzk90jnx {
  fill: currentColor;
  d: path("M2 7V5a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0m15-5h2a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-2a1 1 0 0 1 0-2M4.168 11.445c4.4-6.597 11.264-6.597 15.664 0a1 1 0 0 1 0 1.11c-4.4 6.597-11.264 6.597-15.664 0a1 1 0 0 1 0-1.11M17.779 12c-3.442-4.664-8.116-4.664-11.558 0c3.442 4.664 8.116 4.664 11.558 0M12 11h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2M7 22H5a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2m15-5v2a3 3 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0");
}

</style>
