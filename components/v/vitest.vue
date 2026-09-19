<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3f6ugbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o3f6ugbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vitest" /></template>
