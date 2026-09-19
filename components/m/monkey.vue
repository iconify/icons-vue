<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxpo5pboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxpo5pboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:monkey" /></template>
