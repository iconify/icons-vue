<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqqtj5ncr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iqqtj5ncr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:photo" /></template>
