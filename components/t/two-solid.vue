<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnbwfo_-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnbwfo_-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:two-solid" /></template>
