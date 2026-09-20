<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsoe1tbtj.css';
import '../../css/e/eht21_1kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xsoe1tbtj"/><path class="eht21_1kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:system76" /></template>
