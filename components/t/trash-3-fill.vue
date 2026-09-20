<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_rp64b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_rp64b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trash-3-fill" /></template>
