<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz74811is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lz74811is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:meal" /></template>
