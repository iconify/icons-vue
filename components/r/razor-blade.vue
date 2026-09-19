<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8irw7wpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l8irw7wpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:razor-blade" /></template>
