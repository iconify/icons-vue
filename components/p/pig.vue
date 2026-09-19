<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv6xttrqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sv6xttrqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pig" /></template>
