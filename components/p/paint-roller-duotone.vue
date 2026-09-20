<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t2g5afb-w.css';
import '../../css/f/fuv68jbcx.css';
import '../../css/l/lb_q69l-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t2g5afb-w"/><path class="fuv68jbcx"/><path clip-rule="evenodd" class="lb_q69l-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paint-roller-duotone" /></template>
