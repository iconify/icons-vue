<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og6b60d7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="og6b60d7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:windows11" /></template>
