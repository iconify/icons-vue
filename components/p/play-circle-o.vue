<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9emsibgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w9emsibgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:play-circle-o" /></template>
