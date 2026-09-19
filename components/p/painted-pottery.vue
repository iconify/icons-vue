<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eigw6bc8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eigw6bc8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:painted-pottery" /></template>
