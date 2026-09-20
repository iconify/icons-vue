<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp_rzwbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp_rzwbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-agenda-filled" /></template>
