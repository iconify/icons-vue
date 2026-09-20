<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbwn1hbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbwn1hbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trans-fat" /></template>
