<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndtze0b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ndtze0b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:misdirection" /></template>
