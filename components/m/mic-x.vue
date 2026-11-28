<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8dxtbc8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8dxtbc8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mic-x" /></template>
