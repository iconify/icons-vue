<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we_6prbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="we_6prbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:question-mark-12" /></template>
