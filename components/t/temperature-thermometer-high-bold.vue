<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3os1xhir.css';
import '../../css/d/d6d0x4b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3os1xhir"/><path class="d6d0x4b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:temperature-thermometer-high-bold" /></template>
