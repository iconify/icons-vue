<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/l/le4nw3b-s.css';
import '../../css/e/e4ehvrk0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="l9lv5_bcf wm-k"/><path class="le4nw3b-s wm-a"/><path class="e4ehvrk0f wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:scan-text" /></template>
