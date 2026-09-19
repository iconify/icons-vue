<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hwsal5q-o.css';
import '../../css/l/lst88rrnl.css';
import '../../css/h/hni96jb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="hwsal5q-o"/><path class="lst88rrnl"/><path class="hni96jb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:planet-sat" /></template>
