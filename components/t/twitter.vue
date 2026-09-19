<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh3gsqb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":748.681,"height":1000};
const content = `<path class="zh3gsqb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:twitter" /></template>
