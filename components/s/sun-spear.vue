<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t03n-gbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t03n-gbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sun-spear" /></template>
