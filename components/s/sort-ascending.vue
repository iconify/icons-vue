<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp_jgrb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kp_jgrb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sort-ascending" /></template>
