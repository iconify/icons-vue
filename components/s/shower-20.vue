<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrqyz4i2u.css';
import '../../css/n/nx_frvvuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xrqyz4i2u"/><path class="nx_frvvuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shower-20" /></template>
