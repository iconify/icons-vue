<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb5m_klsf.css';
import '../../css/s/snpiwsb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="sb5m_klsf"/><circle class="snpiwsb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:yellow-circle" /></template>
