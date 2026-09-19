<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-04-nduk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-04-nduk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiral-bottle" /></template>
