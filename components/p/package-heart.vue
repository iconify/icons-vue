<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-zal0bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-zal0bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-heart" /></template>
