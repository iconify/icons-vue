<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vns7f7bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vns7f7bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:waze" /></template>
