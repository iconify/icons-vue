<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knfdt1uek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knfdt1uek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:moebius-star" /></template>
