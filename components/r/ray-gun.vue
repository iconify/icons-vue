<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s32_lyyvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s32_lyyvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ray-gun" /></template>
