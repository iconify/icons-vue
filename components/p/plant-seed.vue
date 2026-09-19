<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8hbyrbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8hbyrbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plant-seed" /></template>
