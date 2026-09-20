<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px5xjv6ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="px5xjv6ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:money-bill-alt" /></template>
