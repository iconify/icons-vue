<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dab7n5b6s.css';
import '../../css/b/b09xt9blt.css';
import '../../css/v/vxn_s1bui.css';
import '../../css/b/bvl3ofrdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGxwCe0cNw" x1="256" x2="256" y1="14.332" y2="497.668" gradientUnits="userSpaceOnUse"><stop offset="0" class="dab7n5b6s"/><stop offset="1" class="b09xt9blt"/></linearGradient><path fill="url(#SVGxwCe0cNw)" class="vxn_s1bui"/><path class="bvl3ofrdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2013" /></template>
