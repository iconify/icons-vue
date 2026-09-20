<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg02rbbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hg02rbbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:menu-down" /></template>
