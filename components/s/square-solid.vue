<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvoz726yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qvoz726yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:square-solid" /></template>
