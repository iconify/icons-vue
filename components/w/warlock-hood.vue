<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4sxe3b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4sxe3b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:warlock-hood" /></template>
