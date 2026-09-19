<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc6p9nboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zc6p9nboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wingfoot" /></template>
