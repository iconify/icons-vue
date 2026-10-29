<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nbh0wg0gi.css';
import '../../css/n/nfcb_rb2q.css';
import '../../css/s/soc2g0bzj.css';
import '../../css/m/mno_rjo8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nbh0wg0gi"/><path class="nfcb_rb2q wm-a"/><path class="soc2g0bzj"/><path class="mno_rjo8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:store-duo" /></template>
