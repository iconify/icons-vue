<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_ad-m_cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ad-m_cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pen-lock" /></template>
