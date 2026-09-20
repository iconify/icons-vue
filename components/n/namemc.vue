<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_q1hyb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_q1hyb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:namemc" /></template>
