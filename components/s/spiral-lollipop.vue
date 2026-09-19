<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reqhr2btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="reqhr2btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiral-lollipop" /></template>
