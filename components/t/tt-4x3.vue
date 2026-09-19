<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vgbcb_s.css';
import '../../css/z/zpcw5vbmj.css';
import '../../css/y/ykg8hrbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="zpcw5vbmj"/><path class="ykg8hrbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:tt-4x3" /></template>
