<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jazau3byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jazau3byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wifi-gear" /></template>
