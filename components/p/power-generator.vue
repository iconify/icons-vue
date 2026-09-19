<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxjr0wsud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxjr0wsud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:power-generator" /></template>
