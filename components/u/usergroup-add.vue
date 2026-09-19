<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmeb-_bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lmeb-_bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:usergroup-add" /></template>
