<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzb42w0ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzb42w0ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:npm" /></template>
