<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y17g8zbpp.css';
import '../../css/f/fqr8fbbds.css';
import '../../css/k/kji6j-bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y17g8zbpp"/><path class="fqr8fbbds"/><path class="kji6j-bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:workflow" /></template>
