<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stiiw_f7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="stiiw_f7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unassigned-work-order" /></template>
