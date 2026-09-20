<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_o0i4b8n.css';
import '../../css/p/p9afdab0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_o0i4b8n"/><path clip-rule="evenodd" class="p9afdab0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sparkles-2-fill" /></template>
