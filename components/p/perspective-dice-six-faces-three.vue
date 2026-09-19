<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx5zfftik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tx5zfftik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-six-faces-three" /></template>
