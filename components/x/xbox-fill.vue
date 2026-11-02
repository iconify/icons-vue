<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me-eke5in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me-eke5in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:xbox-fill" /></template>
