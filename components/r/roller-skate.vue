<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8l419btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8l419btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:roller-skate" /></template>
