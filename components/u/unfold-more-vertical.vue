<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utpl0q-lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utpl0q-lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:unfold-more-vertical" /></template>
