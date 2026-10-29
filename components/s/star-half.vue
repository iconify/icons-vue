<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7ae89syi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ae89syi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:star-half" /></template>
