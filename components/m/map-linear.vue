<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jhf0v4-jb.css';
import '../../css/l/lyfzl0b8c.css';
import '../../css/y/y_h9g_9rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jhf0v4-jb"/><path class="lyfzl0b8c"/><path class="y_h9g_9rq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-linear" /></template>
