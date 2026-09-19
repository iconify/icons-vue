<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkj3kqbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hkj3kqbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:prisma-wordmark" /></template>
