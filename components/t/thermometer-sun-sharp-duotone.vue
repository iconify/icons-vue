<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/dj05c4b-z.css';
import '../../css/d/dgmnhqb1q.css';
import '../../css/x/xcyk673ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dj05c4b-z"/><path class="dgmnhqb1q"/><path class="xcyk673ka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thermometer-sun-sharp-duotone" /></template>
