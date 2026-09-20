<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrzv0hbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrzv0hbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-8-line" /></template>
