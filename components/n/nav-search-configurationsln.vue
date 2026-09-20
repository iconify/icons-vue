<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5ihdvmwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5ihdvmwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-search-configurationsln" /></template>
