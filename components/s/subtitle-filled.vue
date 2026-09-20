<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqzom5m_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqzom5m_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:subtitle-filled" /></template>
