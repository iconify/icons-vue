<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usxh3fzft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usxh3fzft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:meeple-circle" /></template>
