<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/evuq8lbli.css';
import '../../css/o/ozst3gb1r.css';
import '../../css/c/cdghymb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="evuq8lbli"/><circle transform="rotate(-45 8.607 8.879)" class="ozst3gb1r"/><path class="cdghymb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-linear" /></template>
