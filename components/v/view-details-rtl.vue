<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhqtt4b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xhqtt4b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:view-details-rtl" /></template>
