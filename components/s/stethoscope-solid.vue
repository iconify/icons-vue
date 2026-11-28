<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc773cb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc773cb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stethoscope-solid" /></template>
