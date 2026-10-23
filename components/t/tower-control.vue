<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoksa15fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoksa15fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tower-control" /></template>
