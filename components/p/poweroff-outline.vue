<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvopk5nyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bvopk5nyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:poweroff-outline" /></template>
