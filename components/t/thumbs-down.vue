<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix_wpwbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:thumbs-down" /></template>
<style>
.ix_wpwbfp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.16 19.856l3.5-6.5q.09-.167.09-.356v-1q0 2.25 2.25 2.25T22.25 12V5.5q0-2.25-2.25-2.25T17.75 5.5V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 3.25H6.756q-2.432-.019-2.747 2.381l-1.246 6.477l-.007.048q-.156 1.238.673 2.171t2.071.923h4.393l-.388 2.917q-.25 2.244 1.683 2.832q1.841.56 2.936-1.083q.02-.029.036-.06");
}

</style>
