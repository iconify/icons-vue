<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mk-lkrb4b"/><path class="dhwxc28pt"/><circle class="rpun35b8x"/><circle class="mfswmz_uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:right-pointing-magnifying-glass" /></template>
<style>
.dhwxc28pt {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m1.257 29.11l5.88-5.879a2 2 0 0 1 2.828 0l2.828 2.828a2 2 0 0 1 0 2.828l-5.879 5.879a4 4 0 1 1-5.657-5.656");
}

.mfswmz_uk {
  cx: 22.355px;
  cy: 13.669px;
  r: 9.5px;
  fill: var(--svg-color--bbddf5, #bbddf5);
}

.mk-lkrb4b {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("m13.503 19.693l2.828 2.828l-4.95 4.95l-2.828-2.829z");
}

.rpun35b8x {
  cx: 22.355px;
  cy: 13.669px;
  r: 13.5px;
  fill: var(--svg-color--8899a6, #8899a6);
}

</style>
