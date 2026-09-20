<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xui-nrbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xui-nrbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-opacity" /></template>
