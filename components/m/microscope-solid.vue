<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofac2mb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofac2mb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:microscope-solid" /></template>
