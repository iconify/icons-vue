<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-wij4i-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-wij4i-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:subway-sharp" /></template>
