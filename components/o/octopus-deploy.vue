<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u28_fdbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u28_fdbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:octopus-deploy" /></template>
