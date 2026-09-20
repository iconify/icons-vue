<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npwglmbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="npwglmbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wrench-solid" /></template>
