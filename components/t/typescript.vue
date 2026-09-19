<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp7upebym.css';
import '../../css/s/soqzb4g1r.css';
import '../../css/p/p7nsoob7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="soqzb4g1r"/><path class="p7nsoob7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:typescript" /></template>
