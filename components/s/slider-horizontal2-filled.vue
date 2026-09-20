<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke5mo2bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5mo2bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-horizontal2-filled" /></template>
