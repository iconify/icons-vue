<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfyj_sbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfyj_sbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rolodex-outline" /></template>
