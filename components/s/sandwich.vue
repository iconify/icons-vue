<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/y/ya1v57a8r.css';
import '../../css/y/yf6askbee.css';
import '../../css/g/gwga84g0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="ya1v57a8r"/><path class="yf6askbee"/><path class="gwga84g0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sandwich" /></template>
