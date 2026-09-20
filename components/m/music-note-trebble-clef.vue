<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xck5rbc3z.css';
import '../../css/b/b9fa5tbdj.css';
import '../../css/u/uh2amklte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="b9fa5tbdj"/><path class="uh2amklte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:music-note-trebble-clef" /></template>
