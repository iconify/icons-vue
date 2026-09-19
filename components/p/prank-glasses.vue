<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug1uhpbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ug1uhpbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:prank-glasses" /></template>
