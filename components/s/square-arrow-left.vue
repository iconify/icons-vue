<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhwgx5bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhwgx5bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-arrow-left" /></template>
