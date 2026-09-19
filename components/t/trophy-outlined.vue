<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj2nowpcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pj2nowpcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:trophy-outlined" /></template>
