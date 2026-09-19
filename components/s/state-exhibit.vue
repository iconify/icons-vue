<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijtpvlb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ijtpvlb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:state-exhibit" /></template>
