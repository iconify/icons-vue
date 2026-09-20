<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hq7-kg1-l.css';
import '../../css/v/vr39ulzpl.css';
import '../../css/d/d970nk8em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hq7-kg1-l"/><path class="vr39ulzpl"/><path class="d970nk8em"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-linear" /></template>
