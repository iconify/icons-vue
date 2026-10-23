<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc56p8bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc56p8bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scan-face" /></template>
