<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqi1k2b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31.87,"height":32};
const content = `<path class="lqi1k2b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:tools" /></template>
