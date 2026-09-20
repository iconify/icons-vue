<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/g/g_qf3m.css';
import '../../css/c/chu5js.css';
import '../../css/o/oxx-om.css';
import '../../css/t/t-ne3j.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/d/d-jkxijw.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGoWE0Ud5X"><path class="c5xdmn g_qf3m"/><circle class="chu5js"/><path class="c5xdmn oxx-om t-ne3j"/></mask></defs><path mask="url(#SVGoWE0Ud5X)" class="botfzx"/><path class="c5xdmn gd_4-q t-ne3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-alt-off" /></template>
