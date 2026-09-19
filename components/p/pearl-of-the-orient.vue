<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bgju2vbae.css';
import '../../css/h/hu6m7zbrv.css';
import '../../css/i/izz9u2a6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="bgju2vbae"/><circle class="hu6m7zbrv"/><path class="izz9u2a6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pearl-of-the-orient" /></template>
