<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w419r0bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w419r0bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:ppt" /></template>
