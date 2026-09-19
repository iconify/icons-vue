<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff4_qyqlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ff4_qyqlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sanity" /></template>
