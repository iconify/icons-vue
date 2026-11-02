<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3qp9_dtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3qp9_dtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refund-cny-line" /></template>
