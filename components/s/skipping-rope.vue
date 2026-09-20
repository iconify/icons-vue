<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmasnh69x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tmasnh69x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:skipping-rope" /></template>
