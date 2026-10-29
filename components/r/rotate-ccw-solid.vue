<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqq-strpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqq-strpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rotate-ccw-solid" /></template>
