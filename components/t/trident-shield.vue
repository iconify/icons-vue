<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm64734gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xm64734gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trident-shield" /></template>
