<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oguqnobco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oguqnobco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paper-airplane-20-solid" /></template>
