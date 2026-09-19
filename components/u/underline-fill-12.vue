<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkbu5vuyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tkbu5vuyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:underline-fill-12" /></template>
