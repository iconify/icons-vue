<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_080nbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m_080nbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:volume-up" /></template>
