<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6n8dxp_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6n8dxp_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:trash" /></template>
