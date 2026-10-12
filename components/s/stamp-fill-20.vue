<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktay6hbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ktay6hbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:stamp-fill-20" /></template>
