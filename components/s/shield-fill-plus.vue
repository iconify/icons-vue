<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw1gbqudo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yw1gbqudo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield-fill-plus" /></template>
