<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owb878b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="owb878b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stylelint-wordmark" /></template>
