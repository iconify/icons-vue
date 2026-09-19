<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh_fhblyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fh_fhblyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:step-forward-outlined" /></template>
