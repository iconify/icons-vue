<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nskhr0b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nskhr0b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:needle-jaws" /></template>
