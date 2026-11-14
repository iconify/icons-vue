<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubcib3eeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mandarin-orange" /></template>
<style>
.ubcib3eeh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 3.5v1.779q3.04.24 5.26 2.461q2.49 2.489 2.49 6.01t-2.49 6.01T12 22.25t-6.01-2.49Q3.5 17.271 3.5 13.75t2.49-6.01q2.22-2.221 5.26-2.461v-.566q-2.506.886-5.647-1.077q-.179-.112-.274-.301q-.033-.066-.052-.137q-.02-.071-.025-.145t.004-.147t.032-.143q.024-.07.06-.134q.037-.065.085-.12q.049-.056.107-.101q.059-.046.125-.079Q8.982.67 11.383 2.073q.052-.075.12-.135t.149-.102t.169-.064T12 1.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
