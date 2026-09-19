<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5itgc9oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s5itgc9oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:user-switch" /></template>
