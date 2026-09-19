<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjx20x3-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zjx20x3-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:safari-wordmark" /></template>
