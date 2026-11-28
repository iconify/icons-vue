<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9jyzr26n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9jyzr26n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:receipt-x" /></template>
