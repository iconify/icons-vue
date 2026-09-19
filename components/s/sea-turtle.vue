<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_fz9xb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_fz9xb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sea-turtle" /></template>
