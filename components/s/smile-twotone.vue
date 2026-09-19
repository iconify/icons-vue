<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_brepse.css';
import '../../css/x/xtthexbok.css';
import '../../css/q/qy8-hybaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="xtthexbok"/><path class="qy8-hybaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:smile-twotone" /></template>
