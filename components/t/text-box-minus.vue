<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhd83ub7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhd83ub7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text-box-minus" /></template>
