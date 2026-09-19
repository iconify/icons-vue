<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2us3hfma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2us3hfma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rupee" /></template>
