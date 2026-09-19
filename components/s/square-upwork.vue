<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd0jblbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jd0jblbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-upwork" /></template>
