<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va3jfl8-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va3jfl8-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:prometheusio" /></template>
