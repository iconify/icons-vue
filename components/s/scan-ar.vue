<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgor2ducd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgor2ducd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scan-ar" /></template>
