<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly-1yssge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ly-1yssge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pikeman" /></template>
