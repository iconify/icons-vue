<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcmaq_bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wheelchair-fill-sharp" /></template>
<style>
.jcmaq_bia {
  fill: currentColor;
  d: path("M7.158 4.779a2 2 0 1 1 3.684-1.558A2 2 0 0 1 7.158 4.78M10 9h4a1 1 0 0 1 0 2h-4v2h5c.379 0 .725.214.894.553L18.618 19H20a1 1 0 0 1 0 2h-2a1 1 0 0 1-.894-.553L14.382 15H9a1 1 0 0 1-1-1v-1.875a4.002 4.002 0 0 0-.557 7.561A4 4 0 0 0 12.2 18.4a1 1 0 0 1 1.6 1.2a5.9 5.9 0 0 1-2.117 1.767a6 6 0 0 1-8.662-4.864A6.004 6.004 0 0 1 8 10.082V8a1 1 0 0 1 2 0Z");
}

</style>
