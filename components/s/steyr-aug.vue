<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhxbf2bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jhxbf2bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:steyr-aug" /></template>
