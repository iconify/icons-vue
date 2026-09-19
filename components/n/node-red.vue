<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/digtmc1gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="digtmc1gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:node-red" /></template>
