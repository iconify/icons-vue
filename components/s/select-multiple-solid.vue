<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4jpg3bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4jpg3bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:select-multiple-solid" /></template>
