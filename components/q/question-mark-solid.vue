<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr42u6bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr42u6bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:question-mark-solid" /></template>
