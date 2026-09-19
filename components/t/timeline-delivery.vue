<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2-xu8boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="y2-xu8boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:timeline-delivery" /></template>
