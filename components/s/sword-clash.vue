<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq8g_vbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uq8g_vbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-clash" /></template>
