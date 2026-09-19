<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_m_e5evi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_m_e5evi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rapidshare-arrow" /></template>
