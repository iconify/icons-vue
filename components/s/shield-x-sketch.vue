<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pv92h6bei.css';
import '../../css/u/u9ozzachk.css';
import '../../css/h/h46be0bwu.css';
import '../../css/s/s48hxlbad.css';
import '../../css/f/f0ef3bb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pv92h6bei"/><path class="u9ozzachk wm-k"/><path class="h46be0bwu wm-a"/><path class="s48hxlbad wm-k"/><path class="f0ef3bb2k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-x-sketch" /></template>
