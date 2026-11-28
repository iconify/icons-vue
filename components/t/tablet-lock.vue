<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1zg6xa_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1zg6xa_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tablet-lock" /></template>
