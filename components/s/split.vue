<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/g3806gb-b.css';
import '../../css/j/jfdf9lbir.css';
import '../../css/j/j-oll0j4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="g3806gb-b"/><path class="jfdf9lbir"/><path class="j-oll0j4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:split" /></template>
