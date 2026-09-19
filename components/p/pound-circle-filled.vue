<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob82bpbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ob82bpbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pound-circle-filled" /></template>
