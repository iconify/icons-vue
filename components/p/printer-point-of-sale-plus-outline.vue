<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq_i8y-mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq_i8y-mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-plus-outline" /></template>
