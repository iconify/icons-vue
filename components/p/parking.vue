<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow6bvsbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ow6bvsbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:parking" /></template>
