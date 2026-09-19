<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew_sqqbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ew_sqqbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:vertical-left" /></template>
