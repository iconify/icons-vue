<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khb354thf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khb354thf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:ruler-2-line" /></template>
