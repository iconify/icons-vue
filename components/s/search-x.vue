<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixlrgdmxl.css';
import '../../css/i/ifen1pnqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixlrgdmxl"/><path class="ifen1pnqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-x" /></template>
