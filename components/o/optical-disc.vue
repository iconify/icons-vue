<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iut_f7bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="iut_f7bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:optical-disc" /></template>
