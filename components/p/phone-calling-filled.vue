<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp4y0ebkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp4y0ebkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-calling-filled" /></template>
