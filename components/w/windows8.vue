<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af9gyabim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="af9gyabim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:windows8" /></template>
