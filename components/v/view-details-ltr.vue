<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_c9k0a4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m_c9k0a4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:view-details-ltr" /></template>
