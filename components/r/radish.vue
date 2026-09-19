<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/s/s963lnjyn.css';
import '../../css/r/raeld23bm.css';
import '../../css/b/bmnwrrbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s963lnjyn"/><path class="raeld23bm"/><path class="bmnwrrbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:radish" /></template>
