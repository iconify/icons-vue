<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjd-5qbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjd-5qbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stirling-pdf" /></template>
