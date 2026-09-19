<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fl-r0ubyd.css';
import '../../css/v/vyxnsdbwc.css';
import '../../css/p/p5tdlubsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fl-r0ubyd"/><path class="vyxnsdbwc"/><path class="p5tdlubsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:steak" /></template>
