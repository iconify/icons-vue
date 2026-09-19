<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-5fuebxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-5fuebxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pre-prod-environment" /></template>
