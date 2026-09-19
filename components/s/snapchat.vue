<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzw9_9bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yzw9_9bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:snapchat" /></template>
