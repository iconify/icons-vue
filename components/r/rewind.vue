<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc_rtl98b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc_rtl98b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rewind" /></template>
