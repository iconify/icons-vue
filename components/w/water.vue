<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqsf4l63w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hqsf4l63w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:water" /></template>
