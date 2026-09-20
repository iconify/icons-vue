<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lip02cb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pill-off-rounded" /></template>
<style>
.lip02cb7a {
  fill: currentColor;
  d: path("M20 8.625q0 .933-.358 1.775t-1.003 1.508l-1.435 1.415q-.243.243-.566.243t-.565-.243l-5.396-5.396q-.242-.242-.242-.565t.242-.566l1.415-1.435q.666-.646 1.508-1.003T15.375 4q1.927 0 3.276 1.349T20 8.625m-5.494 7.396l-2.598 2.617q-.646.646-1.498 1.004T8.625 20q-1.927 0-3.276-1.349T4 15.375q0-.933.358-1.784q.358-.852 1.004-1.499l2.617-2.598l-4.763-4.763q-.141-.14-.15-.345q-.01-.203.15-.363q.159-.16.353-.16t.354.16l16.154 16.154q.14.14.15.344t-.15.363t-.354.16t-.354-.16z");
}

</style>
