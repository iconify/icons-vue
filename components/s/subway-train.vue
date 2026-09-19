<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai0m27bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ai0m27bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:subway-train" /></template>
