<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0s4xxknq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z0s4xxknq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:migrate" /></template>
