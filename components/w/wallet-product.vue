<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyb_fy_my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyb_fy_my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wallet-product" /></template>
