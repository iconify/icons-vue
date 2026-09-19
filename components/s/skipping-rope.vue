<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1rj6brxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n1rj6brxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skipping-rope" /></template>
