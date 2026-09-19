<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le_b2hb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le_b2hb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-6-filled" /></template>
