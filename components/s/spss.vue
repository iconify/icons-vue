<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u732b2_1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u732b2_1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:spss" /></template>
