<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tws5w2b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tws5w2b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-dashed-kanban" /></template>
