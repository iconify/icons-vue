<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f19j1cczl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f19j1cczl primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spade-duotone" /></template>
