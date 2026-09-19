<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfcvgv5ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfcvgv5ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:wavy-help" /></template>
