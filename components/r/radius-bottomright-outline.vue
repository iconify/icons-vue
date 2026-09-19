<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpxz60bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bpxz60bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:radius-bottomright-outline" /></template>
