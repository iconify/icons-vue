<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6abgzsnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-right-alt-rounded" /></template>
<style>
.g6abgzsnq {
  fill: currentColor;
  d: path("M9 17q-2.075 0-3.537-1.463T4 12t1.463-3.537T9 7q1.825 0 3.188 1.138T13.9 11h4.275l-.9-.9Q17 9.825 17 9.413t.3-.713q.275-.275.7-.275t.7.275l2.6 2.6q.15.15.213.325t.062.375t-.062.375t-.213.325l-2.6 2.6q-.275.275-.687.275T17.3 15.3q-.3-.3-.3-.712t.3-.713l.875-.875H13.9q-.35 1.725-1.713 2.863T9 17");
}

</style>
