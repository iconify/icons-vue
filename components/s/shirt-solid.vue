<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zld1hq7zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zld1hq7zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shirt-solid" /></template>
