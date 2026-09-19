<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4hz6q9ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j4hz6q9ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-array" /></template>
