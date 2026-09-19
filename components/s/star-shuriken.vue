<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8gj4dbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8gj4dbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-shuriken" /></template>
