<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezzt3p5xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ezzt3p5xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tavern-sign" /></template>
