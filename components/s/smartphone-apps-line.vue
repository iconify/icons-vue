<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4i3t7bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4i3t7bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:smartphone-apps-line" /></template>
