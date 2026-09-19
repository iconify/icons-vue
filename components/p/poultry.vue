<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iguir7bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iguir7bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:poultry" /></template>
