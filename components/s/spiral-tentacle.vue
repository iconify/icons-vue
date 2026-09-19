<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke4myvbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ke4myvbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiral-tentacle" /></template>
