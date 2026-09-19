<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1_t2wbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y1_t2wbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:whale-tail" /></template>
