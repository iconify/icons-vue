<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq1pnlb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq1pnlb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-wifi-off-line" /></template>
