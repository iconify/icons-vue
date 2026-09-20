<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apw_yjbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="apw_yjbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spray-paint" /></template>
