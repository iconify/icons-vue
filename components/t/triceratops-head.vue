<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia0pqwm9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia0pqwm9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triceratops-head" /></template>
