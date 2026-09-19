<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0wi9crkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0wi9crkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-05-the-hierophant" /></template>
