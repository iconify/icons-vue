<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9j4j5ave.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9j4j5ave"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shatter" /></template>
