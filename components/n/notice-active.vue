<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aldv0z1kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aldv0z1kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:notice-active" /></template>
