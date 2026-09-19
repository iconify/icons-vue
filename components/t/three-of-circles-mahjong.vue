<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d12u3kbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d12u3kbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:three-of-circles-mahjong" /></template>
