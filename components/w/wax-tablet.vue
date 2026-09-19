<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_0r08bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_0r08bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wax-tablet" /></template>
