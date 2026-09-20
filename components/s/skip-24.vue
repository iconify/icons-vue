<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysa93ccjm.css';
import '../../css/z/zj49idy7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysa93ccjm"/><path class="zj49idy7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:skip-24" /></template>
