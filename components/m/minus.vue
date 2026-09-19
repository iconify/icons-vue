<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3td12bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q3td12bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:minus" /></template>
