<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcq1nd9yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcq1nd9yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-bag-3-line" /></template>
