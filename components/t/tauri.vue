<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-2i06puf.css';
import '../../css/i/i0l09vzyb.css';
import '../../css/n/n_n679b9r.css';
import '../../css/j/jslk2fb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n-2i06puf"/><path class="i0l09vzyb"/><path clip-rule="evenodd" class="n_n679b9r"/><path clip-rule="evenodd" class="jslk2fb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:tauri" /></template>
