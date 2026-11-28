<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ij3vyybgh.css';
import '../../css/c/cir9yb4sp.css';
import '../../css/b/b38cyebvi.css';
import '../../css/n/nor6gcvgk.css';
import '../../css/w/wzsfntb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ij3vyybgh"/><path class="cir9yb4sp"/><path class="b38cyebvi"/><path class="nor6gcvgk"/><path class="wzsfntb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:truck" /></template>
