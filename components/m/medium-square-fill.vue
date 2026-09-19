<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffxjue_mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ffxjue_mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:medium-square-fill" /></template>
