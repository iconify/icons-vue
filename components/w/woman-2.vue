<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp56bzcyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:woman-2" /></template>
<style>
.xp56bzcyx {
  fill: currentColor;
  d: path("M10.673 21.5v-6.115H7.385l2.82-7.108q.232-.554.717-.877q.486-.323 1.083-.323t1.08.324q.481.324.711.88l2.82 7.104h-3.289V21.5zM12 5.808q-.698 0-1.195-.497t-.497-1.195t.497-1.196T12 2.423t1.195.497t.497 1.196q0 .698-.497 1.195T12 5.808");
}

</style>
