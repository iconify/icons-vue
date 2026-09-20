<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3_i8ctrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3_i8ctrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:scale" /></template>
