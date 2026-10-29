<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie42jkbnl.css';
import '../../css/s/s2tb-y15u.css';
import '../../css/m/m_cjgobea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie42jkbnl wm-shadow"/><path class="s2tb-y15u wm-k"/><path class="m_cjgobea wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:square-dashed" /></template>
