<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_m_tibrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_m_tibrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:projects-alt-fill" /></template>
