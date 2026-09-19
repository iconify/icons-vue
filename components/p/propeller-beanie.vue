<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyc-je_on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yyc-je_on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:propeller-beanie" /></template>
