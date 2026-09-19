<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d94-lnnrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d94-lnnrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:winged-shield" /></template>
