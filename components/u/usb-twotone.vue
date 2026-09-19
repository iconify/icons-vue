<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbvvc5y2r.css';
import '../../css/p/pugtge_xh.css';
import '../../css/z/zn2ui6aai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tbvvc5y2r"/><path class="pugtge_xh"/><path class="zn2ui6aai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:usb-twotone" /></template>
