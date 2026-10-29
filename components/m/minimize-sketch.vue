<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hnkx8qb-r.css';
import '../../css/f/fb-ay-bql.css';
import '../../css/s/slrghbbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hnkx8qb-r wm-k"/><path class="fb-ay-bql wm-k"/><path class="slrghbbxr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minimize-sketch" /></template>
