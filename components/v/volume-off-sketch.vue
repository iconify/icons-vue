<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i-_or_22r.css';
import '../../css/l/l8h560gpm.css';
import '../../css/w/w1g8kv4lt.css';
import '../../css/u/uz5aqebtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i-_or_22r"/><path class="l8h560gpm wm-s"/><path class="w1g8kv4lt wm-k"/><path class="uz5aqebtu wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:volume-off-sketch" /></template>
