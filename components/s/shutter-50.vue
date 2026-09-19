<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf36rwkpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf36rwkpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shutter-50" /></template>
