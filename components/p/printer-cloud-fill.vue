<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7kzlph8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7kzlph8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:printer-cloud-fill" /></template>
