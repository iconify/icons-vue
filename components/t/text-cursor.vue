<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/o/oe-98mb0w.css';
import '../../css/m/m5ytp9bms.css';
import '../../css/w/wcaq-jbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="oe-98mb0w wm-k"/><path class="m5ytp9bms wm-a"/><path class="wcaq-jbkf wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:text-cursor" /></template>
