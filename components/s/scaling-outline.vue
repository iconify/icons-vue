<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_wdj5b3k.css';
import '../../css/t/t4y5-pbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_wdj5b3k"/><path class="t4y5-pbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scaling-outline" /></template>
