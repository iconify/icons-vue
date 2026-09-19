<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml9_geb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ml9_geb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:r" /></template>
