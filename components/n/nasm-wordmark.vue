<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrr0sebxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hrr0sebxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nasm-wordmark" /></template>
