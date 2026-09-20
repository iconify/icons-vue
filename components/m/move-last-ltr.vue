<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlnc2n5di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qlnc2n5di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:move-last-ltr" /></template>
