<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5vjwfb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f5vjwfb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:pc" /></template>
