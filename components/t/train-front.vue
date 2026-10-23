<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp5qxlz_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp5qxlz_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:train-front" /></template>
