<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us0x9w4kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="us0x9w4kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:save-template" /></template>
