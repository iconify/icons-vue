<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axem3obyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="axem3obyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:taskade-wordmark" /></template>
