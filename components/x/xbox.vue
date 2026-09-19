<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg1-5rbnm.css';
import '../../css/i/i8-ig2bjx.css';
import '../../css/x/xm9hcq-cp.css';
import '../../css/y/yeyg09bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pg1-5rbnm"/><path class="i8-ig2bjx"/><path class="xm9hcq-cp"/><path class="yeyg09bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:xbox" /></template>
