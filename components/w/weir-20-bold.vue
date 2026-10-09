<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv842m9yr.css';
import '../../css/r/rycvim_ja.css';
import '../../css/h/h49_-cc9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yv842m9yr"/><path class="rycvim_ja"/><path class="h49_-cc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weir-20-bold" /></template>
