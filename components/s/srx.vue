<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqdy2-y3t.css';
import '../../css/f/fs7pu5ekr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdy2-y3t"/><path class="fs7pu5ekr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:srx" /></template>
