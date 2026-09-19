<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uza14gbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uza14gbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-start" /></template>
