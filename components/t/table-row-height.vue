<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3is5gdlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3is5gdlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-row-height" /></template>
