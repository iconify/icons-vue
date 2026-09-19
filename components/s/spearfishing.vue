<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9vs0ebha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9vs0ebha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spearfishing" /></template>
