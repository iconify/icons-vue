<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yimxbdbkz.css';
import '../../css/c/cfhd2dbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yimxbdbkz"/><path class="cfhd2dbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-voice" /></template>
