<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgb78bb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgb78bb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-1-filled" /></template>
