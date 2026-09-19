<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfpp4qbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vfpp4qbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tensorflow" /></template>
