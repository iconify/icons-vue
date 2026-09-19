<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clyynnbbx.css';
import '../../css/z/z-nk8wbnr.css';
import '../../css/x/xy4cuobbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="clyynnbbx"/><path class="z-nk8wbnr"/><path class="xy4cuobbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mail-twotone" /></template>
