<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfz43q1cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tfz43q1cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:whisk" /></template>
