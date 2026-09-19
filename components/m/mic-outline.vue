<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnkgvjblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":416};
const content = `<path class="qnkgvjblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mic-outline" /></template>
