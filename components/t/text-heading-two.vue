<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbsumb_hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbsumb_hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-heading-two" /></template>
