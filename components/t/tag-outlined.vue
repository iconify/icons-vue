<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv9mq4pxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv9mq4pxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:tag-outlined" /></template>
