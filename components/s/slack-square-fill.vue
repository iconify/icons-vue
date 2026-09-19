<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tna4p3b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tna4p3b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:slack-square-fill" /></template>
