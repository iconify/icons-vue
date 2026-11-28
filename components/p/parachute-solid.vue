<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtdojlb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtdojlb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parachute-solid" /></template>
