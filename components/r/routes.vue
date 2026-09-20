<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br-c8m_pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br-c8m_pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:routes" /></template>
