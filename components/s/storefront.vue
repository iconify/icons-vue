<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfhbg6brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfhbg6brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront" /></template>
