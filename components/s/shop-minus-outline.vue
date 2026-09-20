<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tluguxb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tluguxb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shop-minus-outline" /></template>
