<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7ffal8nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k7ffal8nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nano-bot" /></template>
