<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi37w--vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi37w--vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wrench" /></template>
