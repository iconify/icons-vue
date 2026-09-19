<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zakboj_8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zakboj_8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:solar-panel-04" /></template>
