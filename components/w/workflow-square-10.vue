<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sw2wszxbb.css';
import '../../css/n/np4l_rbmm.css';
import '../../css/r/rw82l7faj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sw2wszxbb"/><path class="np4l_rbmm"/><path class="rw82l7faj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:workflow-square-10" /></template>
