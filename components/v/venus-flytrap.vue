<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_rd8mbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_rd8mbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:venus-flytrap" /></template>
