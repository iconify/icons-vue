<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2-ozxjxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2-ozxjxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiky-eclipse" /></template>
