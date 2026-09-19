<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et-6srbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="et-6srbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:webpack" /></template>
