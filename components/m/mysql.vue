<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0v-yo90b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t0v-yo90b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:mysql" /></template>
