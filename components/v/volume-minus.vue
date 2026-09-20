<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj8u2ybur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj8u2ybur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-minus" /></template>
