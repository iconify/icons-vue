<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg9xdvb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vg9xdvb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sperm-whale" /></template>
