<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoo3f_wso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eoo3f_wso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waterfall-20-bold" /></template>
