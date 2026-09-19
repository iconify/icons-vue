<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh97r8j1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rh97r8j1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:pinterest-square" /></template>
