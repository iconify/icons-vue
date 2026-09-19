<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_4vr29tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i_4vr29tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pause-outline-filled" /></template>
