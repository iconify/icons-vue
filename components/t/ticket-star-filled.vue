<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo98_0bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo98_0bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ticket-star-filled" /></template>
