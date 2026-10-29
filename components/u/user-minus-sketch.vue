<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nsj6ylquj.css';
import '../../css/w/wg5tz-s1o.css';
import '../../css/a/a31ecn6xc.css';
import '../../css/p/p2lfr2uwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nsj6ylquj"/><path class="wg5tz-s1o wm-k"/><path class="a31ecn6xc wm-k"/><path class="p2lfr2uwh wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-minus-sketch" /></template>
