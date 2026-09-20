<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj194ubnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj194ubnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront-plus-outline" /></template>
