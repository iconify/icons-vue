<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnac3h90z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vnac3h90z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pendant-key" /></template>
