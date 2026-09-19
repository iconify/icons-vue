<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l39_x8vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l39_x8vnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:saw-claw" /></template>
