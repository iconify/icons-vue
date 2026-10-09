<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hddprfk1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hddprfk1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shapes-20" /></template>
