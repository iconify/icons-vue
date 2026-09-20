<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvaf3v5na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvaf3v5na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:refund-down-light" /></template>
