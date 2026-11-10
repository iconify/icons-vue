<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0pri_qum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m0pri_qum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stackit-wordmark" /></template>
