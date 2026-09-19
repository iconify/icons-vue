<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3d5r3obd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s3d5r3obd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:question-diamond-fill" /></template>
