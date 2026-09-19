<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs2z8bzes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zs2z8bzes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scissors" /></template>
