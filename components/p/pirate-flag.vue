<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4fzrkbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j4fzrkbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pirate-flag" /></template>
