<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciy968brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciy968brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-tower-fill" /></template>
