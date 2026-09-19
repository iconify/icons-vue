<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtt8ubcij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jtt8ubcij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:poland" /></template>
