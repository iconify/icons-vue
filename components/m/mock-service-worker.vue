<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrm3k6bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrm3k6bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mock-service-worker" /></template>
