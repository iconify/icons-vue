<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6h4l0i8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6h4l0i8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:navigation-2" /></template>
