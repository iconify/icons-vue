<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwbkozmxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwbkozmxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-mobile-phone" /></template>
