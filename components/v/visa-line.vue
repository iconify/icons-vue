<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko-91ibce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko-91ibce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:visa-line" /></template>
