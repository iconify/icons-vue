<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq50plqvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bq50plqvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:plus-circle-fill" /></template>
