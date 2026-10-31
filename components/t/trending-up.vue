<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/d/dda7lqbgk.css';
import '../../css/m/mav1xqfkd.css';
import '../../css/w/wnveq1bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="dda7lqbgk wm-k"/><path class="mav1xqfkd wm-a"/><path class="wm-deco wnveq1bjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:trending-up" /></template>
