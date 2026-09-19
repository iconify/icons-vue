<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygvjc2bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygvjc2bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pangolin" /></template>
