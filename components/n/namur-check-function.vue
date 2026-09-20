<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhsx09bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhsx09bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:namur-check-function" /></template>
