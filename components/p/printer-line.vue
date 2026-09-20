<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxil73bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxil73bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:printer-line" /></template>
