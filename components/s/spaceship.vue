<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4bu8tb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4bu8tb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spaceship" /></template>
