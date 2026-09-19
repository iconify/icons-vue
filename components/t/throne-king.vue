<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl2uijbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yl2uijbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:throne-king" /></template>
