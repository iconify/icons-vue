<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/roedmt9no.css';
import '../../css/l/l2h7ekg2x.css';
import '../../css/t/te-vwbyvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="roedmt9no"/><path class="l2h7ekg2x"/><path class="te-vwbyvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet-2" /></template>
