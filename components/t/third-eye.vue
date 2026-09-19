<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix5qpqbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ix5qpqbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:third-eye" /></template>
