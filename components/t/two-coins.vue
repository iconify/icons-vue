<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs5uddbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fs5uddbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:two-coins" /></template>
