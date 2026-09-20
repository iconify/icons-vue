<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm1m_2hku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm1m_2hku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:select-all" /></template>
