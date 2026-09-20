<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf4zkk_tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4zkk_tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wechat-pay-line" /></template>
