<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm3iwqbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gm3iwqbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:piggy-bank-fill" /></template>
