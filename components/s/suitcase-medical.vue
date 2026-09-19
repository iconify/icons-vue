<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehs6s-drt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ehs6s-drt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:suitcase-medical" /></template>
