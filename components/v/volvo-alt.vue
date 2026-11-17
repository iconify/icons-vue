<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia0dl9d3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia0dl9d3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:volvo-alt" /></template>
