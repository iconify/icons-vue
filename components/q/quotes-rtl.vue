<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8s6fwb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i8s6fwb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:quotes-rtl" /></template>
