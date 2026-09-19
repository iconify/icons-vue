<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi_hsf-aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mi_hsf-aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:swagger" /></template>
