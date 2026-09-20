<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e29zf5bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e29zf5bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:network-off-line" /></template>
