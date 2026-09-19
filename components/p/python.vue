<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/x/xvcmqooya.css';
import '../../css/z/z-zny5b2y.css';
import '../../css/a/a3u5zbbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="xvcmqooya"/><path class="z-zny5b2y"/><path class="a3u5zbbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:python" /></template>
