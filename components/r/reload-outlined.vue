<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsr228ivf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qsr228ivf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:reload-outlined" /></template>
