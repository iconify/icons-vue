<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odvnyb7mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="odvnyb7mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-column" /></template>
