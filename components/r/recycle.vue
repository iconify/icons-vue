<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/v/v612o8bte.css';
import '../../css/l/l3czp6bqw.css';
import '../../css/r/rh9qoibkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="v612o8bte wm-k"/><path class="l3czp6bqw wm-a"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:recycle" /></template>
