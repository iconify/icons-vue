<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0lgf8m_j.css';
import '../../css/v/vdullb4tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0lgf8m_j"/><path clip-rule="evenodd" class="vdullb4tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notes-bold" /></template>
