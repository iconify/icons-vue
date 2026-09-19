<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9apc6bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x9apc6bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sliders-outlined" /></template>
