<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6ba4gbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a6ba4gbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-six-faces-four" /></template>
