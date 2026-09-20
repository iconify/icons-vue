<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jbsmz5cgw.css';
import '../../css/i/ida3dz87g.css';
import '../../css/d/dxi3c3bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jbsmz5cgw"/><path class="ida3dz87g"/><path class="dxi3c3bdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-muted" /></template>
