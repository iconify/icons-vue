<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx2izywhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx2izywhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mock-service-worker" /></template>
