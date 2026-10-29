<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s7p4-lb4i.css';
import '../../css/i/i8gtkj1wk.css';
import '../../css/l/l59zwqbwm.css';
import '../../css/k/kpm95pflw.css';
import '../../css/p/p9gzv3y2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s7p4-lb4i"/><path class="i8gtkj1wk"/><path class="l59zwqbwm wm-a"/><path class="kpm95pflw wm-s"/><path class="p9gzv3y2h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:piggy-bank" /></template>
