<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz2_1m_at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz2_1m_at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:menu-2" /></template>
