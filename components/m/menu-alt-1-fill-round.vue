<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs5m_2bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs5m_2bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-1-fill-round" /></template>
