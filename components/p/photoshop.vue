<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9s7o3bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o9s7o3bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:photoshop" /></template>
