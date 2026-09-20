<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj3lfty5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj3lfty5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:shield-off-line" /></template>
