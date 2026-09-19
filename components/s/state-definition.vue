<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9dj_s43h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g9dj_s43h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:state-definition" /></template>
