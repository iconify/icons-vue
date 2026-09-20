<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu6y76b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu6y76b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:postcss" /></template>
