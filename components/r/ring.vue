<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf0nq7tms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qf0nq7tms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ring" /></template>
