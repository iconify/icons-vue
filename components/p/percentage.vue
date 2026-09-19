<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjp61tb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjp61tb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:percentage" /></template>
