<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv3_5ob-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cv3_5ob-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:napster" /></template>
