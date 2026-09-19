<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrko4rbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrko4rbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wooden-helmet" /></template>
