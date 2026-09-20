<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmq1amubh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmq1amubh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-sharp" /></template>
