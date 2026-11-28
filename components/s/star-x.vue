<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4z1vmbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4z1vmbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:star-x" /></template>
