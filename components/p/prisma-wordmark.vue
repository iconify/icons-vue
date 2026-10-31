<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_-88obff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o_-88obff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:prisma-wordmark" /></template>
