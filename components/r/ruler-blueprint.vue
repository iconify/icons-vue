<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yw3ll3bmk.css';
import '../../css/a/a38w6sbvh.css';
import '../../css/p/p6m5mlb1h.css';
import '../../css/o/oeaxk80gc.css';
import '../../css/r/rzoychbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yw3ll3bmk"/><path class="a38w6sbvh wm-deco"/><path class="p6m5mlb1h wm-deco"/><path class="oeaxk80gc wm-k"/><path class="rzoychbjy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ruler-blueprint" /></template>
