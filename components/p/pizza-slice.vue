<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxcoe3bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxcoe3bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pizza-slice" /></template>
