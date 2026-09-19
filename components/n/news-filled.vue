<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq_pm1brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq_pm1brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:news-filled" /></template>
