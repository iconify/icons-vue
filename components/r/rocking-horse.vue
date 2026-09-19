<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wx38zib9k.css';
import '../../css/q/q0mhllb1k.css';
import '../../css/p/pub4l-79m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wx38zib9k"/><path class="q0mhllb1k"/><path class="pub4l-79m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rocking-horse" /></template>
