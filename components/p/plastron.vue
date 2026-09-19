<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llr7bwbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="llr7bwbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plastron" /></template>
