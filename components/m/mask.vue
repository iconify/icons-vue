<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/z01qkqb2l.css';
import '../../css/q/q37jtebrq.css';
import '../../css/n/n92m255cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="z01qkqb2l"/><path class="q37jtebrq"/><path class="n92m255cp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:mask" /></template>
