<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qpm_gor2e.css';
import '../../css/g/g-djhu7tj.css';
import '../../css/m/msmf60bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qpm_gor2e"/><path class="g-djhu7tj"/><path class="msmf60bwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:on-tag" /></template>
