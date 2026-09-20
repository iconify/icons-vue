<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmbla7-hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmbla7-hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sun-rising" /></template>
