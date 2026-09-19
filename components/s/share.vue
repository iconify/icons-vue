<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3lbt79lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w3lbt79lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:share" /></template>
