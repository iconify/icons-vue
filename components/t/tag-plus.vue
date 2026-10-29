<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk19oldpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk19oldpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tag-plus" /></template>
