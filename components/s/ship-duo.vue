<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dvyoy6b_p.css';
import '../../css/y/yexim4dcc.css';
import '../../css/v/v-e4uvn7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dvyoy6b_p"/><path class="yexim4dcc"/><path class="v-e4uvn7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ship-duo" /></template>
