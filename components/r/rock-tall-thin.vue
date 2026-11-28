<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_movwbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m_movwbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:rock-tall-thin" /></template>
