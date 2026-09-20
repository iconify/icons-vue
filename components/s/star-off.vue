<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqr-xj2wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqr-xj2wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-off" /></template>
