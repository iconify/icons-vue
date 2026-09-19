<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_qyv4b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_qyv4b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:sort-descending" /></template>
