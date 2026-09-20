<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kci_ppyst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kci_ppyst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:medical-instrument-scalpel-bold" /></template>
