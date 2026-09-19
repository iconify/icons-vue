<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-6io26x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zw-6io26x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rank-1" /></template>
