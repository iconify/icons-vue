<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yqn6_6bty.css';
import '../../css/q/qui8oyv3s.css';
import '../../css/l/l0uolabhl.css';
import '../../css/u/uv0egcb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yqn6_6bty"/><path class="qui8oyv3s wm-a"/><path class="l0uolabhl wm-k"/><path class="uv0egcb8v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paint-roller-sketch" /></template>
