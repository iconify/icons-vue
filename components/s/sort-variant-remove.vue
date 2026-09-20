<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er_fc8b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er_fc8b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-variant-remove" /></template>
