<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imj3tbb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imj3tbb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mechanical-arm" /></template>
