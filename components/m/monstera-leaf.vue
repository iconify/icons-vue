<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h96_q3ijz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h96_q3ijz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:monstera-leaf" /></template>
