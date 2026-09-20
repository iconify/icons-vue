<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq5yukqvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eq5yukqvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mixx-logo-block" /></template>
