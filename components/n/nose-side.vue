<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eae__35ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eae__35ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nose-side" /></template>
