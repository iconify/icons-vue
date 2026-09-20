<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc75y-sag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc75y-sag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:widget-donut-variant" /></template>
