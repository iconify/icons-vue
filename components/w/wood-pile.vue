<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xumbp4ijn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xumbp4ijn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wood-pile" /></template>
