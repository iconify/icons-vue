<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhhtn6bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jhhtn6bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:researchgate-square" /></template>
