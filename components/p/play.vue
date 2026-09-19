<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0g6m_wze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0g6m_wze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play" /></template>
