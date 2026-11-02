<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6b__b0ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-bulk" /></template>
<style>
.x6b__b0ur {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.833 18.208a2 2 0 0 1-.526 1.899l-.737.738a2.003 2.003 0 0 1-3.079-.305l-2.768-4.153L10 17.535v2.051A2 2 0 0 1 9.414 21l-.207.207a1.578 1.578 0 0 1-2.431-.241l-1.497-2.245l-2.245-1.497a1.578 1.578 0 0 1-.241-2.431L3 14.586A2 2 0 0 1 4.414 14h2.051l1.148-1.723L3.46 9.509a2.003 2.003 0 0 1-.305-3.079l.738-.737a2 2 0 0 1 1.899-.526l6.901 1.726l2.6-2.6c.77-.771 1.784-1.678 2.886-1.899c.99-.197 1.836.207 2.528.899c1.951 1.952.536 3.878-1 5.414l-2.6 2.6Z");
}

</style>
