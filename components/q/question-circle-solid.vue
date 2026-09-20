<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6dnf7-nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6dnf7-nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:question-circle-solid" /></template>
