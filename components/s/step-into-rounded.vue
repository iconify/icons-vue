<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syb5-i0eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:step-into-rounded" /></template>
<style>
.syb5-i0eo {
  fill: currentColor;
  d: path("M9.875 21.125Q9 20.25 9 19t.875-2.125T12 16t2.125.875T15 19t-.875 2.125T12 22t-2.125-.875M11 10.175V3q0-.425.288-.712T12 2t.713.288T13 3v7.175L14.875 8.3q.275-.275.688-.275t.712.275q.3.3.3.713t-.3.712L12.7 13.3q-.3.3-.7.3t-.7-.3L7.7 9.7q-.275-.275-.288-.687T7.7 8.3q.275-.275.7-.275t.7.275z");
}

</style>
