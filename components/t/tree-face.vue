<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvyb1cb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hvyb1cb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tree-face" /></template>
