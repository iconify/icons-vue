<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c99w-65vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c99w-65vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:seven-of-circles-mahjong" /></template>
