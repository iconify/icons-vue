<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz-w0hsyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz-w0hsyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:minus-outline" /></template>
