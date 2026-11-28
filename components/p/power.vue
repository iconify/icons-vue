<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3w5xkbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3w5xkbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:power" /></template>
