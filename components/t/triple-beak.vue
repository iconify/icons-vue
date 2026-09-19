<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad83mhbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ad83mhbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triple-beak" /></template>
