<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc6xhac8s.css';
import '../../css/z/zz3uc3x-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc6xhac8s"/><path class="zz3uc3x-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-bubble-smile" /></template>
