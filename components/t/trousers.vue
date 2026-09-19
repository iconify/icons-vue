<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_a1r3b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_a1r3b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trousers" /></template>
