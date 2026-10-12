<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8c7mwbrw.css';
import '../../css/w/wm5561bcz.css';
import '../../css/i/i8xqukhzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8c7mwbrw"/><path class="wm5561bcz"/><path class="i8xqukhzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:split-20" /></template>
