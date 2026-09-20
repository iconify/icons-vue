<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwfe6tbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gwfe6tbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:network" /></template>
