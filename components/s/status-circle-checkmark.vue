<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti76fbtof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ti76fbtof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:status-circle-checkmark" /></template>
