<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms6cqtber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms6cqtber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spades" /></template>
