<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izsy9-bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izsy9-bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:truck" /></template>
