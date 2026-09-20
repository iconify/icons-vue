<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycd0-xbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycd0-xbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal-circle-solid" /></template>
