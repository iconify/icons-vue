<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2z7jp5ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2z7jp5ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:unplugged" /></template>
