<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8yd5w4xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8yd5w4xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:teapot" /></template>
