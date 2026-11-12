<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng5reibrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ng5reibrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surveyjs-dark" /></template>
