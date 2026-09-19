<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj66m2cnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="aj66m2cnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:spring-wordmark" /></template>
