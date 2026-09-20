<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzc3-d5gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzc3-d5gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plug2" /></template>
