<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l5w8pibgw.css';
import '../../css/k/kn3v5rl7b.css';
import '../../css/h/hn6qrhojp.css';
import '../../css/d/di1d0ffeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l5w8pibgw"/><path class="kn3v5rl7b wm-k"/><path class="hn6qrhojp wm-k"/><path class="di1d0ffeq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mushroom-sketch" /></template>
