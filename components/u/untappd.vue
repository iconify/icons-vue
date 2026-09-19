<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4_opybnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="w4_opybnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:untappd" /></template>
