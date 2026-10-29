<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kydla-v8g.css';
import '../../css/t/twlqflbgi.css';
import '../../css/p/pa-aaynvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kydla-v8g"/><path class="twlqflbgi wm-a"/><path class="pa-aaynvi wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:satellite" /></template>
