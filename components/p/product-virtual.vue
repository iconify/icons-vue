<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc8p4nbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc8p4nbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:product-virtual" /></template>
