<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzh98vb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzh98vb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rain-medium" /></template>
