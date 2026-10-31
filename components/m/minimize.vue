<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/g/goe_53dyv.css';
import '../../css/i/i3vchurfh.css';
import '../../css/n/ns5q66kqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="goe_53dyv wm-k"/><path class="i3vchurfh wm-a"/><path class="ns5q66kqv wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:minimize" /></template>
