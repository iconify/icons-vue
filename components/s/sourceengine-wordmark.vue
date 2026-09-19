<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glb07y6od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="glb07y6od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sourceengine-wordmark" /></template>
