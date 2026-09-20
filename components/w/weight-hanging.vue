<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq2_2eb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dq2_2eb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:weight-hanging" /></template>
