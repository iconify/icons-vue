<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeb0kmifh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":666};
const content = `<path class="yeb0kmifh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:upload" /></template>
