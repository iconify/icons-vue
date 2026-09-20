<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e6k8uxb8f"/><path class="co-0d8brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sis-password-manager" /></template>
<style>
.co-0d8brh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.417 10.5c.6 1.012-1.213 3.123-4.05 4.716s-5.624 2.064-6.224 1.053s1.212-3.123 4.05-4.716c2.836-1.593 5.623-2.064 6.224-1.053");
}

.e6k8uxb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.996 42l12.506-7.72l-2.744-5.305l-5.098 4.176l-2.068-2.9l2.826-2.36l-1.41-4.557l-3.95 3.358l-6.1-8.563c5.854-3.959 9.13-8.464 7.813-10.744c-.558-.967-1.905-1.448-3.863-1.379c-3.169.112-7.61 1.65-11.879 4.115c-7.175 4.143-11.76 9.634-10.24 12.264c1.296 2.228 6.587 1.748 12.81-1.2z");
}

</style>
