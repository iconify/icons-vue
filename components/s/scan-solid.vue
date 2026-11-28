<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quf57ebxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quf57ebxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-solid" /></template>
