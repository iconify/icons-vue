<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3dapca7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3dapca7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:striped-sun" /></template>
