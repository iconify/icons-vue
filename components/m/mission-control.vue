<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9xvuhbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mission-control" /></template>
<style>
.w9xvuhbrh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 3.5h-1.5q-2.5 0-2.5 2.5v4.5q0 1.036.732 1.768T11.25 13v1.5h-6.5q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h14.5q3 0 3-3t-3-3h-6.5V13q1.036 0 1.768-.732t.732-1.768V6q0-1.036-.732-1.768T12.75 3.5M4.25 5H5q2.5 0 2.5 2.5v3q0 1.036-.732 1.768T5 13h-.75q-1.036 0-1.768-.732T1.75 10.5v-3q0-2.5 2.5-2.5M19 5h.75q1.036 0 1.768.732T22.25 7.5v3q0 1.036-.732 1.768T19.75 13H19q-1.036 0-1.768-.732T16.5 10.5v-3Q16.5 5 19 5");
}

</style>
