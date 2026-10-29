<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/g3f5cwbbp.css';
import '../../css/w/wd66k1bjc.css';
import '../../css/l/l8mj6jmuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="g3f5cwbbp"/><path class="wd66k1bjc"/><path class="l8mj6jmuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:radio-tower" /></template>
