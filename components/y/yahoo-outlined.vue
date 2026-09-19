<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ii5ybol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o1ii5ybol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:yahoo-outlined" /></template>
