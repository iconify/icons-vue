<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iug3cpbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iug3cpbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:mongock" /></template>
