<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-61v2bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o-61v2bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:telephone-forward" /></template>
