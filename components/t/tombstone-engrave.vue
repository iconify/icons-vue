<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nn61rl1di.css';
import '../../css/i/ii3dpwb6w.css';
import '../../css/l/l5w9p4b0i.css';
import '../../css/p/p-cqkx0gi.css';
import '../../css/l/lixim-bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nn61rl1di wm-k"/><path class="ii3dpwb6w wm-a"/><path class="l5w9p4b0i wm-shadow"/><path class="p-cqkx0gi wm-k"/><path class="lixim-bjn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tombstone-engrave" /></template>
