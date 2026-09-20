<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt5zlcqpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt5zlcqpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-x" /></template>
