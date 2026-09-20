<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o95zvjb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o95zvjb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage-circle-solid" /></template>
