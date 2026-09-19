<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgoae7bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mgoae7bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:wire" /></template>
