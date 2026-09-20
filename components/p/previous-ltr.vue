<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-8x0zb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o-8x0zb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:previous-ltr" /></template>
