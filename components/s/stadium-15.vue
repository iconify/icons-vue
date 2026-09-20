<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke938i2kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ke938i2kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:stadium-15" /></template>
