<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfpjjmbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfpjjmbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-orientation" /></template>
