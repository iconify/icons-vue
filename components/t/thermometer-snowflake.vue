<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t193o3bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t193o3bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:thermometer-snowflake" /></template>
