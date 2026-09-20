<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-zf5sbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-zf5sbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tick-square-filled" /></template>
