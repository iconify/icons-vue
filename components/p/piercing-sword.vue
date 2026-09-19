<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx_m927ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nx_m927ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:piercing-sword" /></template>
