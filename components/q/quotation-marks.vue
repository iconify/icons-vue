<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-ce26b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-ce26b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:quotation-marks" /></template>
