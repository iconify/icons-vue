<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9oaitb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w9oaitb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:python" /></template>
