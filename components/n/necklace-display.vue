<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3j-4zoln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3j-4zoln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:necklace-display" /></template>
