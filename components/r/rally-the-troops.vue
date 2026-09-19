<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8e47hb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8e47hb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rally-the-troops" /></template>
