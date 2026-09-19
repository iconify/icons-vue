<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2w92b9qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2w92b9qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tablet" /></template>
