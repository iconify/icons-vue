<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgedu3jvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgedu3jvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spline-solid" /></template>
