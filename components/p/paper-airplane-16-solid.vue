<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo9vs-bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qo9vs-bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paper-airplane-16-solid" /></template>
