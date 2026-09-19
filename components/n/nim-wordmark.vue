<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecyf0d8eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ecyf0d8eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nim-wordmark" /></template>
