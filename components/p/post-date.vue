<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gi87txbdj.css';
import '../../css/h/hdcm3gbmg.css';
import '../../css/y/ymly3jbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="gi87txbdj"/><path vector-effect="non-scaling-stroke" class="hdcm3gbmg"/><path vector-effect="non-scaling-stroke" class="ymly3jbab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-date" /></template>
