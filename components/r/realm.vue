<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a36d3kanx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a36d3kanx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:realm" /></template>
