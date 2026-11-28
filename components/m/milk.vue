<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q32m6k_1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q32m6k_1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:milk" /></template>
