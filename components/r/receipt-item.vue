<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jbe9hb-ly.css';
import '../../css/s/sudgglpna.css';
import '../../css/w/wib9mkn2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jbe9hb-ly"/><path class="sudgglpna"/><path class="wib9mkn2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt-item" /></template>
