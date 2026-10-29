<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll9t1wp4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll9t1wp4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:orbit" /></template>
