<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di_uw2ssz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-tie" /></template>
<style>
.di_uw2ssz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.641 4.141Q7.25 5.532 7.25 7.5t1.391 3.359T12 12.25t3.359-1.391T16.75 7.5t-1.391-3.359T12 2.75T8.641 4.141M3.25 20q0-2.83 2.685-4.612Q8.402 13.75 12 13.75t6.065 1.638Q20.75 17.17 20.75 20q0 1.75-1.75 1.75H5q-1.75 0-1.75-1.75m9.95-5.231q-.468-.561-1.2-.561t-1.2.561l-.103.123q-.785.942-.419 2.112l.381 1.22q.309.985 1.341.985t1.341-.985l.381-1.22q.366-1.17-.42-2.113z");
}

</style>
