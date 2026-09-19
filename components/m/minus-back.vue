<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qygkojtyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qygkojtyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:minus-back" /></template>
