<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir2_d-n7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ir2_d-n7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ndz" /></template>
