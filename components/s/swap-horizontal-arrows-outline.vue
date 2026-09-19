<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_cx-qbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="m_cx-qbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:swap-horizontal-arrows-outline" /></template>
