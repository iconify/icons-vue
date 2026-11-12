<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txhr-1syo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="txhr-1syo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sublimetext" /></template>
