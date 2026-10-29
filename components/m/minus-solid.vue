<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs-s1wbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs-s1wbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minus-solid" /></template>
