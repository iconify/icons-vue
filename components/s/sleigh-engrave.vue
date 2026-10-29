<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/exq1o42bg.css';
import '../../css/w/w2ktjvbtb.css';
import '../../css/b/bqbzijb2c.css';
import '../../css/t/ti18yabmh.css';
import '../../css/p/p9pn97g5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="exq1o42bg wm-k"/><path class="w2ktjvbtb wm-a"/><path class="bqbzijb2c wm-shadow"/><path class="ti18yabmh wm-k"/><path class="p9pn97g5g wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sleigh-engrave" /></template>
