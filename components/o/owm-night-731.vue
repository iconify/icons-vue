<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf8yx3bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="wf8yx3bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-731" /></template>
