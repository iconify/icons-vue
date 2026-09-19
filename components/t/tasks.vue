<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz9fz5bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="tz9fz5bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:tasks" /></template>
