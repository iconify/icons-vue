<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np37u6blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="np37u6blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:picture-edit" /></template>
