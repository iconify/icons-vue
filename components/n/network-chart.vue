<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trq-q2bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trq-q2bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:network-chart" /></template>
