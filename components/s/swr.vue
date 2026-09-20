<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx2vqp2yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx2vqp2yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:swr" /></template>
