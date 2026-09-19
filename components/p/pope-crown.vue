<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji4w1hy1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ji4w1hy1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pope-crown" /></template>
