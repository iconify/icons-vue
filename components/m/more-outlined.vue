<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge1denbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ge1denbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:more-outlined" /></template>
