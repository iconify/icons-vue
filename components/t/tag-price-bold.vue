<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m73gp0u2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m73gp0u2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-price-bold" /></template>
