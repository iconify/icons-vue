<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-pq1rbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-pq1rbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wifi-high" /></template>
