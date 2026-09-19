<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/puzwzylem.css';
import '../../css/t/tk0yztb4f.css';
import '../../css/z/z-pb6vbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="puzwzylem"/><path class="tk0yztb4f"/><path class="z-pb6vbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-lock-check-01" /></template>
