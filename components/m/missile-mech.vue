<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe0m_79-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fe0m_79-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:missile-mech" /></template>
