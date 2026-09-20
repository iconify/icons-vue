<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8h4q4b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8h4q4b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:maplibre" /></template>
