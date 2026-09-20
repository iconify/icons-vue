<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onkvqv5wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onkvqv5wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wechat-pay-line" /></template>
