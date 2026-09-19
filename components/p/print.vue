<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj5hqvbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="dj5hqvbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:print" /></template>
