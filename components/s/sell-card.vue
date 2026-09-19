<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqa_9q7yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tqa_9q7yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sell-card" /></template>
