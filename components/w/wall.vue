<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9ly5k7oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9ly5k7oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:wall" /></template>
