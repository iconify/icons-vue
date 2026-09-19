<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gepffur1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="gepffur1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-dashboard" /></template>
