<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eln99ybja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eln99ybja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:transaction-minus" /></template>
