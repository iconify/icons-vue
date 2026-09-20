<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlt7m_b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlt7m_b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:triangle-alert" /></template>
