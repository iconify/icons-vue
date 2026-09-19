<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7e4hvb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h7e4hvb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mountain-cave" /></template>
