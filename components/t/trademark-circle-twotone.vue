<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_brepse.css';
import '../../css/a/a-ahklbmq.css';
import '../../css/i/ioh29v_qh.css';
import '../../css/h/h9k680llf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="a-ahklbmq"/><path class="ioh29v_qh"/><path class="h9k680llf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:trademark-circle-twotone" /></template>
