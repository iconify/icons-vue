<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sku-uqfty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sku-uqfty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mars4" /></template>
