<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx80fdgqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xx80fdgqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:play-square-fill" /></template>
