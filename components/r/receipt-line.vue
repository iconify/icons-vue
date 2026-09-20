<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvlitmbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvlitmbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:receipt-line" /></template>
