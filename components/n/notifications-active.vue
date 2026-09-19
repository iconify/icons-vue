<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yilqdacnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":432};
const content = `<path class="yilqdacnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:notifications-active" /></template>
