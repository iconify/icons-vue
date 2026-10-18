<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb5q3pedd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb5q3pedd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:utensils" /></template>
