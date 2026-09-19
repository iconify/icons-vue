<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9f86gbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t9f86gbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pc" /></template>
