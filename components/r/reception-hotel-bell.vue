<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx328_b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx328_b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:reception-hotel-bell" /></template>
