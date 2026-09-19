<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs-8xlbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs-8xlbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:smartphone-fill" /></template>
