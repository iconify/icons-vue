<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqfbf6-1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqfbf6-1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scalpel-strike" /></template>
