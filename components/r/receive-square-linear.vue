<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/prbf6mb6m.css';
import '../../css/f/fa28zot1y.css';
import '../../css/p/pw8f5c0fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="prbf6mb6m"/><path class="fa28zot1y"/><path class="pw8f5c0fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:receive-square-linear" /></template>
