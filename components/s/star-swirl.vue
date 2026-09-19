<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-ed3c-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cd-ed3c-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-swirl" /></template>
