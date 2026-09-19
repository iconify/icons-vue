<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls6_xn_4i.css';
import '../../css/e/e9xcq6pkk.css';
import '../../css/d/dox57-bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="e9xcq6pkk"/><path class="dox57-bsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ninja" /></template>
