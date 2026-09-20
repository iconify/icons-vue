<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l54d8tb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l54d8tb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:zap" /></template>
