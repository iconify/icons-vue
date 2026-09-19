<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy21kjbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy21kjbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-align-center" /></template>
