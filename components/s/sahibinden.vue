<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikp2_-bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ikp2_-bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sahibinden" /></template>
