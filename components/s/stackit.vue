<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe--k8x1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xe--k8x1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:stackit" /></template>
