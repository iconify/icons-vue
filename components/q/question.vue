<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3q_3eikd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3q_3eikd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:question" /></template>
