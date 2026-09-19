<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/misnlkb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="misnlkb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:remedy" /></template>
