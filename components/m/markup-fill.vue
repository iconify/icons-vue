<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg3wgt3ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg3wgt3ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:markup-fill" /></template>
