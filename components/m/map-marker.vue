<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u148y6bbs.css';
import '../../css/r/re4cghb4q.css';
import '../../css/c/cz14bobdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="u148y6bbs"><path class="re4cghb4q"/><path class="cz14bobdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:map-marker" /></template>
