<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kflq1srsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kflq1srsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:warning-line" /></template>
