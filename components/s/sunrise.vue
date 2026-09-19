<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_76vphk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru_76vphk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sunrise" /></template>
