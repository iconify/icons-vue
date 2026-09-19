<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jib32ub8s.css';
import '../../css/q/qvm7p4brn.css';
import '../../css/d/d3r-gqy_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jib32ub8s"/><path class="qvm7p4brn"/><path class="d3r-gqy_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:video-camera-twotone" /></template>
