<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtyf1vuiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dtyf1vuiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:shopping-filled" /></template>
