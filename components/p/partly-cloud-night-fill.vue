<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtgo2qbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtgo2qbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:partly-cloud-night-fill" /></template>
