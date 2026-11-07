<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvac8qbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvac8qbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volleyball-2-linear" /></template>
