<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qto-1actj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qto-1actj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:markdown" /></template>
