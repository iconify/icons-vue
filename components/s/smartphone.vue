<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_aow6bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_aow6bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:smartphone" /></template>
