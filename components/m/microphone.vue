<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxl5ucr5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxl5ucr5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:microphone" /></template>
