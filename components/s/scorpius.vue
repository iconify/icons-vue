<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="m7_ntsblm"/><path class="rf9l19-po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:scorpius" /></template>
<style>
.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.m7_ntsblm {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.5 28L26 24v8z");
}

.rf9l19-po {
  fill: var(--svg-color--fff, #fff);
  d: path("M27 26.5c-3.842 0-4-.933-4-4.5V11c0-3.979-1.776-4.939-3.268-5.291c-1.465-.345-2.971.291-4.024 1.269a3.5 3.5 0 0 0-1.976-1.269c-1.46-.345-2.959.286-4.012 1.257C8.705 5.619 7.393 5.5 7 5.5a1.5 1.5 0 1 0 0 3c.155 0 1 .646 1 3.5v11a1.5 1.5 0 1 0 3 0l.006-13.086a1.502 1.502 0 0 1 3.004 0L14 23a1.5 1.5 0 1 0 3 0l.006-13.086a1.502 1.502 0 0 1 3.004 0L20 22c0 3.952.535 7.5 7 7.5a1.5 1.5 0 0 0 0-3");
}

</style>
