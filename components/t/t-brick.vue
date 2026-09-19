<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj7h58bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nj7h58bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:t-brick" /></template>
