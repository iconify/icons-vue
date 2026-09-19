<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6qls-h6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6qls-h6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:soil-reading" /></template>
