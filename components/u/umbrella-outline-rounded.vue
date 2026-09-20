<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj0w_2ees"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:umbrella-outline-rounded" /></template>
<style>
.nj0w_2ees {
  fill: currentColor;
  d: path("m12.5 17.935l3.2-9.796l-1.535.398L12.5 7.3zm-1 0V7.3L9.834 8.562l-1.578-.443zm.216 3.489q-.118-.076-.185-.253L7.21 8.141q-.143-.46.18-.805q.324-.345.783-.22l1.443.348L11.5 6.025V3.4q0-.788.58-1.344T13.5 1.5t1.42.556t.58 1.344q0 .214-.143.357T15 3.9t-.357-.143T14.5 3.4q0-.43-.294-.703t-.706-.272t-.706.291q-.294.292-.294.684v2.625l1.885 1.439l1.442-.348q.46-.125.783.22t.18.805l-4.32 13.005q-.068.177-.186.266T12 21.5t-.284-.076");
}

</style>
