<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjjt68bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mjjt68bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vine-flower" /></template>
