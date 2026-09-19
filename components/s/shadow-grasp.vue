<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzek_iukp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nzek_iukp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shadow-grasp" /></template>
