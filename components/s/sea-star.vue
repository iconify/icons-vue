<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwm7y7b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dwm7y7b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sea-star" /></template>
