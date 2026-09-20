<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd00cbc6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nd00cbc6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-arrow-bottom-left" /></template>
