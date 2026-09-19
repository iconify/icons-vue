<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-bp5d1bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-bp5d1bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:round-shield" /></template>
