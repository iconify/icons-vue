<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxb4accij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sxb4accij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shambling-mound" /></template>
