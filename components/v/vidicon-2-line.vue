<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k91r18brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k91r18brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vidicon-2-line" /></template>
