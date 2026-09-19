<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysp0zgcvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ysp0zgcvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tree-swing" /></template>
