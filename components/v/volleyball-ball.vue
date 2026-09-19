<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2wj4l62v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2wj4l62v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:volleyball-ball" /></template>
