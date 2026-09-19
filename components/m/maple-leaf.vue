<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2q56mb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2q56mb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:maple-leaf" /></template>
