<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efy6mqwgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="efy6mqwgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:swagger" /></template>
