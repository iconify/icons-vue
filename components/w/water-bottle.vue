<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q656w8_df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q656w8_df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-bottle" /></template>
