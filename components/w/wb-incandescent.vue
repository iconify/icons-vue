<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omq1hqcfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omq1hqcfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wb-incandescent" /></template>
