<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz-04ekur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oz-04ekur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-left-header" /></template>
