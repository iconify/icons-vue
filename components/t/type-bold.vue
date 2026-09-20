<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl4t4gbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl4t4gbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:type-bold" /></template>
