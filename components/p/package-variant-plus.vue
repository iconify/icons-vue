<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdbrfshop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdbrfshop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-variant-plus" /></template>
