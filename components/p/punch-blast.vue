<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5-lecc5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5-lecc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:punch-blast" /></template>
