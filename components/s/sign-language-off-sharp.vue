<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0vl3f3hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sign-language-off-sharp" /></template>
<style>
.o0vl3f3hr {
  fill: currentColor;
  d: path("m2.667 21.221l.118-.988l4.019.329l.725-2.521l-5.685-1.056l.197-.983l5.763 1.07l.656-2.258l-6.508-1.787l.294-.925l6.489 1.729l.817-2.844l-7.46-7.48L2.8 2.8l18.4 18.4l-.708.708l-4.83-4.806l-.677 2.46q-.318 1.175-1.325 1.869q-1.008.694-2.227.569zm15.225-6.179l-5.107-5.134l.984-.71l-3.944-5.902l.798-.586l3.95 5.927l1.962-1.427l-2.066-4.935l.914-.41l2.886 6.899l2.11-2.341l1.388.748l-1.451 5.587q-.112.423-.354.739q-.243.317-.571.534zm-3.867-.992L4.812 9.298l.496-.89l6.383 3.308z");
}

</style>
