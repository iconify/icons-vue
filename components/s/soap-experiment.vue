<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvw0jng_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tvw0jng_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:soap-experiment" /></template>
