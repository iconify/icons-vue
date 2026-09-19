<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylkgm9bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ylkgm9bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:take-my-money" /></template>
