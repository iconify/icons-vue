<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/w/w1dp8qb9i.css';
import '../../css/s/skgel1llp.css';
import '../../css/i/i49wp7b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="w1dp8qb9i"/><path class="skgel1llp"/><path class="i49wp7b0m wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:playground" /></template>
