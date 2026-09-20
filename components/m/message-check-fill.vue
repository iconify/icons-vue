<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_90szbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_90szbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-check-fill" /></template>
