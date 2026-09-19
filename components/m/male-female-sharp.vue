<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4erq1bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e4erq1bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:male-female-sharp" /></template>
