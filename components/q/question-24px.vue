<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv7h-h8kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv7h-h8kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:question-24px" /></template>
