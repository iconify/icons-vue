<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs6sa0e_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gs6sa0e_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:uv" /></template>
