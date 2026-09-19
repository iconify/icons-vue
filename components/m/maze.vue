<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v39fq-b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v39fq-b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:maze" /></template>
