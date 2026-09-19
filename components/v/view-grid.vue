<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt4poo8_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt4poo8_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:view-grid" /></template>
