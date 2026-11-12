<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgq1n4jen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgq1n4jen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:volvo-alt" /></template>
