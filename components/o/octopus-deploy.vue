<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvig-vcjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cvig-vcjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:octopus-deploy" /></template>
