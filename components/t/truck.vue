<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vop63v7-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="vop63v7-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:truck" /></template>
