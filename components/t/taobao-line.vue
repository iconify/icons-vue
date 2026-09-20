<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stdd_k7yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stdd_k7yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:taobao-line" /></template>
