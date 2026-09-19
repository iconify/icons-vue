<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u60sa06dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u60sa06dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:postman" /></template>
