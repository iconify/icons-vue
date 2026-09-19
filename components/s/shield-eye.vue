<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vthw3ebcn.css';
import '../../css/r/r0it_tiwo.css';
import '../../css/v/vt6fgp66q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vthw3ebcn"/><path class="r0it_tiwo"/><path class="vt6fgp66q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield-eye" /></template>
