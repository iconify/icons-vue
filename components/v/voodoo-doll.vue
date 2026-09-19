<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i336q6bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i336q6bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:voodoo-doll" /></template>
