<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_re_zmcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_re_zmcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:microsoft-bing" /></template>
