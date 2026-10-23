<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc4lmzb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc4lmzb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:squircle-dashed" /></template>
