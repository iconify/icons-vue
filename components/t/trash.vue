<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjz1nm3be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qjz1nm3be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:trash" /></template>
