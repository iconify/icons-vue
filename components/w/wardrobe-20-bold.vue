<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydzth1mww.css';
import '../../css/v/vf8m8ubqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ydzth1mww"/><path class="vf8m8ubqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wardrobe-20-bold" /></template>
