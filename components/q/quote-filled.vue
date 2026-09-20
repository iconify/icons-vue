<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrqyk9bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrqyk9bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:quote-filled" /></template>
