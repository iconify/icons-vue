<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pej5vegmf.css';
import '../../css/s/sqh-tvbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pej5vegmf"/><path class="sqh-tvbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-crash" /></template>
