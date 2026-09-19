<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/macoowb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="macoowb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-six-faces-six" /></template>
