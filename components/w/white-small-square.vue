<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbxb9zycx.css';
import '../../css/u/uu386rb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="nbxb9zycx"/><path class="uu386rb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-small-square" /></template>
