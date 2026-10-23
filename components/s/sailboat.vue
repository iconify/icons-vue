<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woo5_fmvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woo5_fmvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sailboat" /></template>
