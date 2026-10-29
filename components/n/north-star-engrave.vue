<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kafw2jbbs.css';
import '../../css/b/b6p07tn5i.css';
import '../../css/z/zib8m2_fq.css';
import '../../css/e/eacle5s9s.css';
import '../../css/u/u0km1qbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kafw2jbbs wm-k"/><path class="b6p07tn5i wm-a"/><path class="wm-shadow zib8m2_fq"/><path class="eacle5s9s wm-k"/><path class="u0km1qbun wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:north-star-engrave" /></template>
