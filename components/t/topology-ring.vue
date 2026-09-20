<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huqn5m_ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huqn5m_ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-ring" /></template>
