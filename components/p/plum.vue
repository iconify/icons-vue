<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqoxu7b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqoxu7b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plum" /></template>
